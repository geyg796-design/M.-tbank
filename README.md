# UST Credit Union — Android APK Project

This is a complete Android Studio/Gradle project for building an APK that opens the existing UST Credit Union simulated web application.

## Build with GitHub Actions

1. Create a GitHub repository named `USTCreditUnion`.
2. Upload **all contents of this folder** to the repository root. The `.github` folder must also be uploaded.
3. Commit the files to the `main` branch.
4. Open the repository's **Actions** tab.
5. Select **Build APK**.
6. Tap **Run workflow**.
7. Wait for the green checkmark.
8. Open the completed workflow run.
9. Under **Artifacts**, download `UST-Credit-Union-APK`.
10. Extract the downloaded ZIP and install `app-debug.apk` on your Android phone.

## If GitHub says the workflow is missing

Make sure this path exists exactly:
`.github/workflows/build-apk.yml`

Also make sure you uploaded the **contents** of this project, not only the outer ZIP file.

## Application

The APK loads:
https://harborbank-personal-bfnrh8.v2.appdeploy.ai/

The app is a simulated banking interface. It does not connect to real bank accounts, payment networks, Zelle, Cash App, or other financial systems.

## Android requirements

- Android 6.0 (API 23) or newer
- Internet connection to load the hosted application
