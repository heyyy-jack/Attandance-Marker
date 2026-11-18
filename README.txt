COACHING MANAGER — v2.0
Made by Jack

FILES
Keep index.html, manifest.webmanifest, sw.js and the icons/ folder together.

RUN IT
- Quick test: open index.html in Chrome or Edge.
- Install + offline support (Windows): open Command Prompt in this folder and run
    py -m http.server 8000
  then open http://localhost:8000 and use the browser's "Install app" option.

DATA
- Students, attendance, marks and settings are saved in this browser on this device.
- Nothing syncs between devices. Use Backup (download JSON) and Restore regularly.
- Data saved by the earlier "Attendance Marker" version is picked up automatically.

ATTENDANCE %
Present / (Present + Absent) x 100. Leave is excluded.

TABS
- Attendance: tap P / A / L per student. "Mark all present" only fills unmarked students.
- Day-wise: all saved records by date, filter by month, class, or name; export CSV.
- Students: add, edit, remove. Shows each student's attendance % for the current month.
- Marks: enter 7 subjects out of 100 per student per month, with live total and grade.
- Report: printable monthly report card (marks + attendance).
- Cards: printable monthly attendance card with a ring chart.
- Settings: theme, institute name on printouts, low-attendance threshold, backup, About.

PRINTING
Use "Print / PDF" on the Report or Cards tab, then choose "Save as PDF" in the print dialog.
