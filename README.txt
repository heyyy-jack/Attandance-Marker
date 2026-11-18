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

App icons are included in icons/icon-192.png and icons/icon-512.png and are configured for installable app shortcuts.

DAY-WISE RECORDS
- Open the Day-wise tab to view saved attendance grouped by date.
- Filter by month, class/group, or student name/roll number.
- Use All dates to view the full attendance history.
- Export the filtered records to CSV.

NOTE
The uploaded HTML used as the base contains a Class / group field. It does not currently contain a separate Section field.


Marks and monthly report cards:
- Open Marks to enter monthly marks for English, Hindi, Mathematics, Science, Social Science, Computer, and General Knowledge (each out of 100).
- Open Report to generate and print/save a monthly academic report card with subject marks, percentage, grade, and attendance summary.
- Marks are stored locally in this browser and included in JSON backups.


Latest update:
- App name changed to Manager.
- Settings includes the institute name used on generated attendance and academic report cards.
- Settings displays the creator credit: Made by Raj.
- Report cards use a refreshed premium blue layout.
