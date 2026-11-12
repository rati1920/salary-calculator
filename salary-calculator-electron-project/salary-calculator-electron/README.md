# Salary Calculator Desktop App

## Build locally
1. Install Node.js 20 LTS.
2. Open a terminal in this folder.
3. Run `npm install`.
4. Run `npm start` to test the app.
5. Run `npm run dist` to build the Windows installer into `dist/`.

## Build using GitHub Actions
1. Create a new GitHub repository.
2. Upload all files and folders from this project.
3. Open the repository's **Actions** tab.
4. Select **Build Windows EXE**.
5. Click **Run workflow** and confirm.
6. Wait for the green check mark.
7. Open the completed workflow run and find **Artifacts** at the bottom.
8. Download `Salary-Calculator-Windows-Installer` and extract the ZIP.
9. Run `Salary-Calculator-Setup-1.0.0.exe` on your Windows computer.

The monthly history is stored in the app's local browser storage on that computer.
