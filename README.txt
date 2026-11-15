ANANT ATTENDANCE — UPDATED PACKAGE

This package uses your uploaded anant-attendance.html as index.html.
It also includes the PWA manifest and service worker required by the HTML file.

QUICK TEST
1. Extract the ZIP.
2. Open index.html in Chrome to test the app.

INSTALL + OFFLINE SUPPORT ON WINDOWS
1. Keep index.html, manifest.webmanifest and sw.js together in the same folder.
2. Open Command Prompt in this folder.
3. Run: py -m http.server 8000
4. Open http://localhost:8000 in Chrome or Edge.
5. Use the browser's Install app option.

DATA
- Student and attendance data are stored in this browser on this device.
- Data does not automatically sync between laptop and phone.
- Use Backup regularly; use Restore to import a JSON backup.
- Keep a copy of backups somewhere safe.

ATTENDANCE CALCULATION
The app calculates attendance as Present / (Present + Absent) × 100.
Leave is excluded from the percentage.

Update: Student records now include an optional Section field. Section is shown in attendance, student directory and monthly cards, with filters for attendance and the directory. Existing student data remains compatible; older records simply have no section until edited.

App icons are included in icons/icon-192.png and icons/icon-512.png and are configured for installable app shortcuts.
