# Curtain Wall Calculator — Windows desktop build

This repository wraps the supplied standalone HTML calculator in Electron and builds a Windows NSIS installer through GitHub Actions.

## Build

1. Upload all repository files to the root of a GitHub repository.
2. Open **Actions** → **Build Windows Installer**.
3. Select **Run workflow** (or push to `main`).
4. Open the completed workflow run and download the artifact named `Curtain-Wall-Calculator-Windows-Installer`.
5. Extract the artifact ZIP and run the `.exe` installer.

The installed application loads the local `index.html`; the application itself does not need an internet connection. GitHub needs internet access during the build to download npm packages.

## Local development (optional)

Requires Node.js. Run `npm install`, then `npm start`.
