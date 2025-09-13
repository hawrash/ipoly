# ipoly


## 📚 Polytechnic Student Schedule Builder

A mobile-first web app designed specifically for **Polytechnic students** to easily manage and view their weekly class schedules — with a clean, color-coded interface inspired by real-world schedule systems (like IUOB).

![WhatsApp Image 2025-09-13 at 3 05 36 AM](https://github.com/user-attachments/assets/e21d3fb8-96db-4a3c-ba3b-3ce383ad7666)


---

## 📝 Description

The **Polytechnic Student Schedule Builder** is a powerful yet easy-to-use scheduling app for Polytechnic students. With support for course names, codes, sections, times, and classrooms, this app automatically organizes your classes into a clear weekly schedule.

Whether you’re juggling multiple modules or trying to avoid class clashes, this app helps you stay organized.

---

## 🎯 Features

- 🔐 **Login / Register**
  - Secure student accounts (optional if offline/local)
  
- 🧾 **Course Management (CRUD)**
  - Add, edit, and delete course entries (code, section, room, time)
  
- 🗓 **Automatic Weekly Schedule Builder**
  - Clean UI with day-by-day blocks
  - Detects **conflicts** in timing
  - Color-coded by subject/module
  
- 📱 **Mobile-First Responsive Design**
  - Designed for phones and tablets (like the sample screenshot)
  - Touch-friendly interactions
  
- 👨‍🎓 **Student-Specific Data**
  - Each student sees only their personalized schedule

---

## 🧪 Example Schedule (Based on Screenshot)

| Time        | Monday           | Tuesday          | Wednesday        | Thursday         | Friday           |
|-------------|------------------|------------------|------------------|------------------|------------------|
| 08:00–09:00 | ACC112 (S18-117) | ITB1105 (S49-030) | ACC112 (S18-117) | ITB1105 (S49-030) | ACC112 (S18-117) |
| 09:00–10:00 | ARAB101 (S35-101)| ECON140 (S18-217)| ARAB101 (S35-101)| ECON140 (S18-217)| ARAB101 (S35-101)|
| 10:00–11:00 | HIST122 (S18-217)| HIST122 (S18-217)| HIST122 (S18-217)| HIST122 (S18-217)| HIST122 (S18-217)|
| 13:00–14:00 | MATHS104 (S18-217)| MATHS104 (S18-217)| MATHS104 (S18-217)| MATHS104 (S18-217)| MATHS104 (S18-217)|

> This sample reflects a real Polytechnic student schedule. The app automatically generates this view when the student enters their modules and section details.

---

## 🚀 Getting Started

### Live Demo

[🔗 Link to deployed app (if available)]

### Local Development

1. **Clone the repo**

```bash
git clone https://github.com/your-username/poly-schedule-builder.git
```

2. **Backend Setup (Django / FastAPI)**

```bash
cd backend
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

3. **Frontend Setup (React or Django templates)**

```bash
cd frontend
npm install
npm start
```

4. **Visit in Browser**

- React: `http://localhost:3000`
- Django: `http://127.0.0.1:8000`

---

## 🧰 Tech Stack

| Area        | Tech Used           |
|-------------|---------------------|
| Backend     | Django / FastAPI     |
| Frontend    | React / HTML/CSS     |
| Database    | SQLite / PostgreSQL  |
| Styling     | Tailwind / Bootstrap |
| Layout      | Flexbox / CSS Grid   |
| Deployment  | Render / Heroku / Vercel |

---

## 💡 Future Features

- 📤 Export Schedule as **PDF**
- ⏰ Add **reminders** for assignments or exams
- 🔄 Import schedule from **Polytechnic APIs** or CSV
- 🎨 Support **themes** and **dark mode**
- 📱 Drag-and-drop interface for manual schedule adjustments

---

## 🙌 Attributions

- **IUOB** – Interface Inspiration
- **React** – Frontend Framework
- **Django / FastAPI** – Backend Logic & API
- **Tailwind / Bootstrap** – UI Styling

---

## 📄 License

Licensed under the **MIT License**. Free for educational and personal use.

---

## 📷 Screenshots

Here’s what it looks like:

<img src="images.png" width="300" alt="Polytechnic Student Schedule Builder UI" />
