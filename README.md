# 📘 Offline Attendance System (Editable)

A simple **offline, browser-based attendance system** that stores all data in your browser’s **localStorage** — no server required.  
You can manage subjects, teachers, students, and attendance records completely offline, with full editing and export options.

## ✨ Features

- **Subject & Teacher Management**
  - Add, edit, and delete subjects
  - Change teacher names anytime

- **Student Management**
  - Add, edit, and delete students
  - Student edits automatically update past attendance

- **Attendance Tracking**
  - Mark daily attendance as **Present**, **Leave**, or **Absent**
  - Edit past attendance records by date
  - Save data locally (persists even after closing the browser)

- **Export to Excel**
  - Download attendance records in `.xlsx` format for sharing or record keeping

## 🖼 Screenshots

*(Add screenshots here)*

## 🚀 How to Use

1. **Download** the file:
   - [offline_attendance_editable.html](offline_attendance_editable.html)

2. **Open** the file in any modern web browser (Chrome, Edge, Firefox, etc.)

3. **Manage Subjects & Teachers**
   - Add a new subject and assign a teacher
   - Use the dropdown to select an existing subject
   - Use the delete button to remove a subject completely

4. **Manage Students**
   - Add students for the selected subject
   - Edit or delete students as needed

5. **Mark Attendance**
   - For today’s date: select **Present**, **Leave**, or **Absent** for each student
   - Click **Save Attendance**

6. **Edit Past Attendance**
   - Select a past date from the date picker
   - Load and edit attendance for that day
   - Save changes

7. **Export**
   - Click **Export Excel** to download the attendance report

## 📦 Technology Used

- **HTML5, CSS3, JavaScript**
- **[SheetJS (xlsx)](https://github.com/SheetJS/sheetjs)** for Excel export
- **localStorage** for offline data persistence

## 📌 Notes

- All data is saved **only in your browser**. Clearing your browser’s site data will remove your attendance records.
- Works completely offline — no internet connection required.
- Compatible with desktop and mobile browsers.

## 🛠 Future Improvements

- Password protection for teacher/owner
- Multi-class dashboard view
- Data backup/import from Excel

---

**Author:** *Your Name Here*  
📅 *Last Updated:* YYYY-MM-DD
