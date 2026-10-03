# SorenWare — One ZIP → Automatic APK Build

## Upload from phone

1. Create a GitHub repository named `SorenWare`.
2. Upload these two items to the repository root:
   - `SorenWare_Project.zip`
   - `.github/workflows/build-from-zip.yml`
3. Open **Actions** → **Build SorenWare from ZIP**.
4. Tap **Run workflow**.
5. When it finishes, open **Artifacts** and download `SorenWare-debug-apk`.

The workflow extracts the ZIP on the GitHub runner and builds the debug APK.
