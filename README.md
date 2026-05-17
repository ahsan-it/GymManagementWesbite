# GymManagement# 🏋️ PeakX Fitness — Gym Website

A clean, responsive **gym membership website** built with **Python Flask** and pure **HTML/CSS**. Features a bold dark + orange design with a home page, about page, and membership plans.

---

## 📸 Preview

> Dark-themed fitness website with an orange accent color, hero section, stats bar, and membership pricing cards.

---

## 📁 Project Structure

```
PeakX/
│
├── app.py                  # Flask application & routes
│
├── templates/
│   ├── home.html           # Home page (hero + stats)
│   ├── about.html          # About page (story + features)
│   └── membership.html     # Membership plans (pricing cards)
│
└── static/
    └── style.css           # Global stylesheet
```

---

## ✨ Features

- ✅ **3 Pages** — Home, About, Membership
- ✅ **Flask Backend** — Python-powered routing with Jinja2 templates
- ✅ **Fully Responsive** — works on desktop, tablet, and mobile
- ✅ **Dark + Orange Theme** — bold gym-style color palette
- ✅ **Stats Bar** — member count, coaches, hours, programs
- ✅ **Pricing Cards** — 3 membership tiers with featured highlight
- ✅ **No database required** — simple and lightweight

---

## 🛠️ Tech Stack

| Technology | Usage |
|---|---|
| Python 3 | Backend language |
| Flask | Web framework & routing |
| HTML5 | Page structure and templates |
| CSS3 | Styling, Flexbox, responsive layout |
| Jinja2 | Template engine (built into Flask) |

---

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/ahsan-it/GymManagementWesbite.git
cd GymManagementWesbite
```

### 2. Install Flask
```bash
pip install flask
```

### 3. Set up folders
Make sure your structure matches:
```
templates/   ← put home.html, about.html, membership.html here
static/      ← put style.css here
app.py       ← in the root folder
```

### 4. Run the app
```bash
python app.py
```

### 5. Open in browser
```
http://127.0.0.1:5000
```

---

## 🔗 Routes

| Route | Page | Description |
|---|---|---|
| `/` | Home | Hero section + stats bar |
| `/about` | About Us | Gym story + feature highlights |
| `/membership` | Membership | Pricing plans (Foundation, Athlete, Champion) |

---

## 💰 Membership Plans

| Plan | Price | Highlights |
|---|---|---|
| Foundation | Rs 1,800 / month | Gym floor, 3 group classes/week |
| **Athlete** ⭐ | Rs 3,200 / month | Unlimited classes, PT sessions, diet plan |
| Champion | Rs 5,800 / month | Dedicated coach, 5 PT sessions, progress tracking |

---

## 🎨 Color Palette

| Color | Hex | Usage |
|---|---|---|
| Jet Black | `#0a0a0a` | Navbar, hero background |
| Orange | `#f97316` | Accent, buttons, highlights |
| Off White | `#fafafa` | Card backgrounds |
| Mid Grey | `#888` | Subtext and descriptions |

---

## 📝 License

This project was built for **educational purposes**.  
Feel free to fork, modify, and use it as a starter template.

---

> Made with 🔥 by **Muhammad Ahsan Abid**Wesbite
This is a gym management website using flask
