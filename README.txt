TINY ZOO - BUILD THE APK IN THE CLOUD (no installs on your computer)

1. Make a free account at github.com and click New repository (name: tinyzoo, Private is fine).
2. Click "uploading an existing file". Drag in package.json, capacitor.config.json and the whole "www" folder.
3. Click "Add file > Create new file". In the name box type exactly:
   .github/workflows/android.yml
   Paste the contents of android.yml (from the .github/workflows folder of this zip) and click Commit.
4. Open the "Actions" tab. A run called "Build APK" starts by itself (about 5-10 minutes).
5. When it shows a green check, open the run and download "TinyZoo-apk" at the bottom (Artifacts).
6. Unzip it, send app-debug.apk to your phone, tap it, allow "install unknown apps", install.
