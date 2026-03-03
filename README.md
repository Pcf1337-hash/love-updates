# Love Tracker — App Updates

Dieses Repository hostet die APK-Releases der Love Tracker App.

## Neues Update veröffentlichen

1. **APK bauen:** `eas build --profile preview` → `app-release.apk` herunterladen
2. **Neuen Release erstellen:**
   - GitHub → Releases → "Draft a new release"
   - Tag: `v1.4.0` (Versionsnummer anpassen)
   - Title: `Love Tracker v1.4.0`
   - `app-release.apk` als Asset anhängen
   - "Publish release" klicken
3. **Supabase aktualisieren:**
   ```sql
   UPDATE public.app_updates
   SET update_available = 1,
       version_old = '1.3.0',
       version_new = '1.4.0',
       apk_url = 'https://github.com/USERNAME/love-updates/releases/download/v1.4.0/app-release.apk'
   WHERE id = (SELECT id FROM public.app_updates LIMIT 1);
   ```
4. **Update deaktivieren** (nach erfolgreichem Rollout):
   ```sql
   UPDATE public.app_updates SET update_available = 0;
   ```

## Release-URL Format

```
https://github.com/USERNAME/love-updates/releases/download/v{VERSION}/app-release.apk
```
