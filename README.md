<p align="center">
  <img src="assets/logo.png" alt="L & H Bethel School logo" width="180">
</p>

<h1 align="center">L &amp; H Bethel School — Student Manager</h1>

<p align="center">
  Mission Veng, Leimakhong · Estd 2024<br>
  Version 4.0
</p>

---

The Student Manager is an offline school-office app. It is a single HTML file and needs no server, database or internet connection. All records are encrypted and stored **only in the browser on the computer where you use it**.

## Features

- Student admissions, classes, sections and promotion
- Attendance (students and hostel)
- Fees, payments, concessions, receipts and fee slips
- Examinations, marks and printable reports
- ID cards (single and bulk A4 sheets) and certificates
- Hostel rooms and stays, staff and salaries, timetable
- Staff logins with password-protected, AES-encrypted records
- Compressed encrypted backups (`.mcbak`) and restore

## How to use

### Option 1: On a single computer (recommended for the school office)

1. Download this repository (**Code → Download ZIP**) and extract it.
2. Open `index.html` in **Google Chrome** or **Microsoft Edge**.
3. Create the Administrator login the first time you open it.

### Option 2: Online with GitHub Pages

1. In this repository, go to **Settings → Pages**.
2. Under **Build and deployment**, set **Source** to *Deploy from a branch*, choose `main` and `/ (root)`, then click **Save**.
3. After a minute the app is live at `https://<your-username>.github.io/<repository-name>/`.

> **Note:** Even on GitHub Pages, records are still stored only in the browser of each computer that opens the page. Nothing is uploaded to GitHub. Each browser and each web address keeps its own separate data. To move records from the offline file to the online page, or between computers, use **Download backup** and **Restore**.

## Privacy and backups

- **Never upload backup files (`.mcbak` / `.json`) to this repository.** They contain student information. The included `.gitignore` blocks them, but take care when uploading files through the GitHub website.
- Download a backup regularly and keep it somewhere safe and private.
- Passwords cannot be reset. If every admin password is lost, the records cannot be opened.

## Changing the school name or logo

The school name, address, phone and logo can be changed inside the app under **Settings**. The default logo is built into `index.html`, and a copy is in [`assets/logo.png`](assets/logo.png).

## Repository layout

| Path | Contents |
| --- | --- |
| `index.html` | The complete app |
| `assets/logo.png` | School logo |
| `docs/START_HERE.txt` | Full user guide and version history |
| `docs/TESTING.txt` | Testing checklist |

In the docs, `LH_Bethel_Student_Manager.html` refers to the same app, which is called `index.html` in this repository.

## Credits

Developed by Hegin Haokip.
