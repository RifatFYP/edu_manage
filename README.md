[![Download Releases](https://img.shields.io/badge/Download-Releases-blue?style=for-the-badge&logo=github)](https://github.com/RifatFYP/edu_manage/releases)

# edu_manage

Full-stack educational platform built with React, Node.js, Express, and MongoDB. Supports multi-user roles, file uploads, attendance tracking, and course analytics for modern educational institutions.

## 🚀 Getting Started

This guide helps a non-technical user download and run edu_manage from the Releases page. The releases page contains packaged installers for Windows, macOS, and Linux. Pick the installer for your computer, download it, and follow these steps to open the app.

You do not need to know programming. The installer bundles the web app, the server, and a small local database so the app runs on your computer like a regular program.

Contents you will find in this README:
- How to reach the Releases page
- How to pick the right file for your computer
- How to install and run the app on Windows, macOS, or Linux
- Basic setup after first run
- Troubleshooting and how to update

## 📥 Download & Install

Visit this page to download:
https://github.com/RifatFYP/edu_manage/releases

How to pick the right asset on the Releases page:
- Windows: choose a file that ends with .exe or .msi
- macOS: choose a file that ends with .dmg or .zip
- Linux: choose a file that ends with .AppImage, .deb, or .tar.gz

Step-by-step download and install

1. Click the blue badge at the top or open the link above to go to the Releases page.
2. Find the latest release. The latest release is listed near the top with a date.
3. Under "Assets" choose the file that matches your operating system. The file names contain the OS name.
4. Download the file to your computer. Save it to your Downloads folder.

After download, follow the section below for your operating system.

## ✅ Run the App — Windows

1. Open File Explorer and go to your Downloads folder.
2. Double-click the file that ends with .exe or .msi.
3. If Windows asks for permission, click Run or Yes.
4. Follow the installer steps. Use the default options if you are not sure.
5. When the installer finishes, you will get a desktop shortcut or a Start menu entry named "edu_manage".
6. Double-click the shortcut to open the app.

What happens when the app opens
- The app runs a local server and opens a browser window.
- The app may take 10–30 seconds to prepare on first run.
- You will see a setup screen to create an admin user.

## ✅ Run the App — macOS

1. Open Finder and go to your Downloads folder.
2. Double-click the .dmg file or unzip the .zip file.
3. If you opened a .dmg, drag the edu_manage icon to the Applications folder.
4. Open Applications and double-click edu_manage.
5. If macOS warns about opening an app from an unidentified developer, open System Preferences > Security & Privacy and click Open Anyway, then open the app again.
6. The app will open in a browser and show the setup screen.

## ✅ Run the App — Linux

1. Open your Downloads folder in your file manager.
2. If the asset is AppImage:
   - Right-click the file, choose Properties, then Permissions, then allow executing the file as a program.
   - Double-click the AppImage to run it.
3. If the asset is .deb:
   - Double-click the .deb file and install with your package installer.
4. If the asset is tar.gz:
   - Right-click and choose Extract. Open the extracted folder and run the included start script (usually start.sh). If the file does not run, open a terminal in that folder and run:
     ./start.sh
5. The app opens in your browser and shows the setup screen.

## ⚙️ First-Time Setup

1. Create an admin account:
   - Enter a name, an email, and a password you will remember.
   - Write down your password in a safe place.
2. Add a school or institution name if the app asks for it.
3. Add a course to test:
   - Go to Courses > Add Course
   - Enter a course name and description
4. Create a sample user for a teacher and a student.
5. Upload one sample file to the course to check file upload.

Default content and demo data
- The installer includes demo data so you can try features before adding real data.
- Demo accounts do not connect to the internet or to external systems.

## 🧾 System Requirements

Minimum (for small classes or testing)
- CPU: 2 cores
- RAM: 4 GB
- Disk: 2 GB free
- OS: Windows 10 or later, macOS 10.14 or later, Ubuntu 18.04 or later

Recommended (for regular use with many users)
- CPU: 4 cores
- RAM: 8 GB or more
- Disk: 10 GB free
- Network: Internet access for updates

The installer bundles Node.js and a local MongoDB instance. You do not need to install them manually.

## 🛠️ Troubleshooting

If the app will not open
- Check that you completed the install steps and allowed the app to run.
- Restart your computer and try again.
- If an antivirus or security app blocks the installer, look for a message in the antivirus app and allow the installer.

If the browser shows "Connecting" for a long time
- Wait 20–60 seconds on the first run. The app starts services on first run.
- If the problem persists, open Task Manager or Activity Monitor and look for a process named edu_manage or node. If you do not see it, restart the app.

If you see database errors
- Restart the app. The installer includes a built-in database and it restarts with the app.
- If problems persist, find the log files in the app folder:
  - Windows: C:\Users\<YourName>\AppData\Local\edu_manage\logs
  - macOS: ~/Library/Application Support/edu_manage/logs
  - Linux: ~/.local/share/edu_manage/logs
- Share the most recent log file when you contact support.

If you cannot upload files
- Check that the file size is under the default limit (50 MB). You can split large files into smaller parts.
- Ensure you have write permission to the folder you selected for downloads.

## 🔄 Update the App

1. Open the same Releases page:
   https://github.com/RifatFYP/edu_manage/releases
2. Download the latest installer for your OS.
3. Run the installer. The installer will update the existing installation and keep your data.
4. Restart the app after the update.

Auto-update
- Some releases include an auto-update option you can enable in Settings > Updates.
- If you enable auto-update, the app checks for updates and prompts you to install them.

## 🔒 Data & Privacy

Where your data lives
- The app stores data on your computer in a local database folder.
- Uploaded files live in a folder inside the app data folder.

Backups
- You can export a backup from Settings > Backup.
- Save backups to an external drive or cloud storage.

Privacy
- The app does not send your data to third parties by default.
- Optional integrations (email, analytics) require your explicit consent.

## 📬 Support

If you need help:
- Check the FAQ in the app under Help > FAQ.
- Send an email to support@edu-manage.local with:
  - A clear description of the problem
  - The OS you use (Windows, macOS, Linux)
  - The log file from the logs folder

When you report a problem, include the exact text of any error messages and the steps you used before the problem occurred.

## 🔧 Common Features (at a glance)

- Multi-role access: Admin, Teacher, Student, Parent
- File uploads: Assignments and course materials
- Attendance: Mark and export attendance records
- Course analytics: View course engagement and performance
- User management: Add and remove users, set roles
- Local backups: Export and import data

Visit the Releases page to download:
https://github.com/RifatFYP/edu_manage/releases