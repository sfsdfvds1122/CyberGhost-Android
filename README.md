# CyberGhost Android starter project

This is a starter Android project, not a full clone of the previously uploaded APK. It includes a GitHub Actions workflow to build a debug APK.

## Build from a phone
1. Create a GitHub repository and upload the contents of this folder (including the hidden `.github` folder).
2. Open the repository's **Actions** tab.
3. Select **Build CyberGhost APK**, then choose **Run workflow**.
4. When the run completes, open it and download the `CyberGhost-debug-apk` artifact.

The APK is unsigned for Play Store distribution but can be installed manually after allowing installs from the browser/files app.
