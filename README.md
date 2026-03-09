# VP Command Centre
### Samsidh School, Narsapur — Vice Principal Dashboard

A complete school management dashboard for the VP office. Tracks tasks, academic events, revision plans, timetables, and connects to AI for daily briefings.

---

## 🚀 Deploy to GitHub Pages (5 minutes)

1. Create a new GitHub repository — name it `vp-command-centre`
2. Upload `index.html` to the repository
3. Go to **Settings → Pages**
4. Under **Source** select `main` branch → `/ (root)`
5. Click **Save**
6. Your app will be live at: `https://YOUR-USERNAME.github.io/vp-command-centre`

---

## ⚙️ Connect to Apps Script (AI Chat + Exports)

1. Open your Apps Script project at script.google.com
2. Click **Deploy → New Deployment**
3. Select type: **Web App**
4. Set **Execute as**: Me
5. Set **Who has access**: Anyone
6. Click **Deploy** → Copy the Web App URL
7. Open your dashboard → go to **Settings**
8. Paste the URL in **Apps Script Web App URL**
9. Click **Save**

AI chat and exports will now work.

---

## 📦 What's Included

| Module | Description |
|--------|-------------|
| Dashboard | Daily overview — urgent tasks, this week, academic alerts |
| Tasks | Add/manage VP tasks with priority, type, reminders |
| Calendar | Monthly view with task and event dots |
| Academic Planner | Add exams, PTMs, holidays, events with alerts |
| Revision Plans | Track teacher-submitted revision plans |
| Timetables | Store and view class timetables |
| AI Assistant | Chat with Groq AI about your school data |
| Briefing History | View past morning briefings |
| LMS Tracker | Paste syllabus data from your Python scripts |
| Exports | Trigger Google Sheet exports via Apps Script |

---

## 💾 Data Storage

All data saves in your browser's localStorage. Nothing is sent externally except AI chat queries (via your own Apps Script) and export triggers.

---

## 🔗 Stack

- Frontend: Pure HTML/CSS/JS — no frameworks, no dependencies
- AI: Groq (Llama 3.3 70B) via Google Apps Script
- Database: Supabase (PostgreSQL)
- Hosting: GitHub Pages (free)
- Automation: Google Apps Script triggers
