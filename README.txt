COACHING MANAGER — v2.1
Made by Jack

FILES
Keep index.html, manifest.webmanifest, sw.js and the icons/ folder together.

RUN IT
- Quick test: open index.html in Chrome or Edge.
- Install + offline support (Windows): open Command Prompt in this folder and run
    py -m http.server 8000
  then open http://localhost:8000 and use the browser's "Install app" option.

DATA
- Everything is saved in this browser on this device. Nothing syncs automatically.
- Backup: download a JSON file. Restore offers two choices:
    Replace - swaps this browser's data for the backup.
    Merge   - adds the backup's students, attendance and marks to what is already here
              (use this to combine two devices' records).
- Data saved by the earlier "Attendance Marker" / v2.0 versions is picked up automatically.

STUDENTS
- Import CSV: download "Get template", fill it in (Excel: Save As > CSV), then Import CSV.
  Columns: name, class, roll, phone, admission_date (YYYY-MM-DD or DD/MM/YYYY).
  Duplicates (same name, class and roll) are skipped.

ATTENDANCE
- Tap P / A / L per student. "Mark all present" fills only unmarked students.
- Absentees for the selected date get a WhatsApp button that opens a ready-made message
  to the parent number. Edit the wording in Settings. Numbers without a country code are
  treated as Indian (+91).
- Attendance % = Present / (Present + Absent) x 100. Leave is excluded.

MARKS & SUBJECTS
- Settings > Subjects & max marks: rename, add, remove subjects, and set each one's maximum.
- Marks entry shows a live total, percentage and grade. Report cards use the same subjects.

OVERVIEW
- Month summary, six-month attendance trend, and a class-wise table of attendance and marks.

APP LOCK
- Settings > App lock sets a 4 to 8 digit PIN. The app asks for it on opening.
- This keeps casual users out. It does not encrypt the stored data.
- Forgot PIN? The only way back in is to delete all app data (you lose local data, so back up first).

PRINTING
Use "Print / PDF" on the Report or Cards tab, then choose "Save as PDF" in the print dialog.
