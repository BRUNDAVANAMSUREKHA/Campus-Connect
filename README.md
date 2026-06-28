<div align="center">

<img src="https://readme-typing-svg.herokuapp.com?font=DM+Sans&size=32&duration=3000&pause=1000&color=10B981&center=true&vCenter=true&width=700&lines=Campus+Connect+🎓;KLU+Campus+Services+App;Transport+Booking+%2B+Food+Ordering;Built+with+Python+%2B+Tkinter" alt="Typing SVG" />

<br/>

# 🎓 Campus Connect
### *KLU Campus Services — All in One Desktop GUI Application*

<br/>

[![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Tkinter](https://img.shields.io/badge/Tkinter-GUI-10B981?style=for-the-badge&logo=python&logoColor=white)](https://docs.python.org/3/library/tkinter.html)
[![Pillow](https://img.shields.io/badge/Pillow-Image_Processing-yellow?style=for-the-badge)](https://pillow.readthedocs.io/)
[![Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20Mac%20%7C%20Linux-blue?style=for-the-badge)](https://www.python.org/)
[![License](https://img.shields.io/badge/License-Proprietary-red?style=for-the-badge)](LICENSE)

</div>

---

## 📌 Overview

**Campus Connect** is a A Python Desktop GUI Application built with Tkinter that brings essential KLU campus services to a single, easy-to-use interface. Students and staff log in with their KLU email and can instantly book campus transport or order food from any of the three campus canteens — all without leaving their desk.

> 🔐 *Only valid `@klu.ac.in` email addresses are accepted — ensuring the app is exclusive to KLU students and staff.*

---

## 🖥️ App Flow

```
Launch App
    ↓
🔐 Login Screen
   Enter @klu.ac.in email + password
    ↓
🏠 Main Menu
   ┌─────────────────┬──────────────────┐
   │  🚌 Transport   │  🍽️ Food Order   │
   └─────────────────┴──────────────────┘
        ↓                    ↓
  Vehicle Selection     Choose Canteen
  ┌──────────────┐    ┌──────────────────────┐
  │  🚑 Ambulance│    │  🍛 Nalabagam        │
  │  ⚡ E-Vehicle│    │  🍽️ Sudexo           │
  └──────────────┘    │  🍱 Northern Canteen │
        ↓             └──────────────────────┘
  Enter Source &               ↓
  Destination          Choose Category
        ↓         (Breakfast/Rice/Curries/
  ✅ Booking        Snacks/Desserts/Sweets)
  Confirmed                    ↓
                        Browse & Order Items
                               ↓
                        ✅ Order Confirmed
```

---

## ✨ Features

### 🔐 Login System
- Accepts only **`@klu.ac.in`** email addresses
- Secure password entry with masked input
- Invalid credentials show an error popup
- KLU campus background image on login screen

---

### 🚌 Transportation Booking
Choose between two vehicle types:

| Vehicle | Use Case |
|---|---|
| 🚑 **Ambulance** | Medical emergencies on campus |
| ⚡ **Electric Vehicle** | Campus commuting and transport |

- Enter **Source** and **Destination** locations
- Click **Book Vehicle** → instant confirmation popup
- Radio button selection for vehicle type

---

### 🍽️ Food Ordering

**3 Campus Canteens available:**

| Canteen | Categories Available |
|---|---|
| 🍛 **Nalabagam** | Breakfast, Rice Items, Curries, Snacks |
| 🍽️ **Sudexo** | Breakfast, Rice Items, Curries, Snacks, Desserts |
| 🍱 **Northern Canteen** | Breakfast, Rice Items, Curries, Desserts, Sweets |

**Food Items per Category:**

| Category | Items |
|---|---|
| 🌅 Breakfast | Idli, Dosa, Upma, Puri, Pesarattu |
| 🍚 Rice Items | Veg Biryani, Chicken Biryani, Pulao, Fried Rice, Curd Rice |
| 🍛 Curries | Paneer Butter Masala, Chole, Dal Makhani, Mixed Veg Curry |
| 🥪 Snacks | Samosa, Pakora, Spring Rolls, Sandwich |
| 🍮 Desserts | Gulab Jamun, Rasgulla, Ice Cream, Halwa |
| 🍬 Sweets | Laddu, Jalebi, Barfi |

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| **Python 3.x** | Core programming language |
| **Tkinter** | GUI windows, buttons, labels, frames |
| **ttk (Themed Tkinter)** | Styled rounded buttons |
| **Pillow (PIL)** | Load and resize background images |
| **messagebox** | Booking and order confirmation popups |

---

## 📁 Project Structure

```
Campus-Connect/
│
├── main.py                    # Entire application code
│
└── 📂 images/
    ├── klu.jpg                # Login & main menu background
    ├── Transportation.jpg     # Transport button image
    ├── FoodOrdering.jpg       # Food ordering button image
    ├── Road.jpg               # Vehicle selection background
    ├── Ambulance.jpg          # Ambulance radio button image
    ├── Electronicvehicle.jpg  # Electric vehicle radio button image
    ├── FoodOrderingSystem.jpg # Food ordering window background
    ├── Nalabakam.jpg          # Nalabagam canteen image
    ├── Sudexo.jpg             # Sudexo canteen image
    ├── Northendcanteen.jpg    # Northern canteen image
    ├── Vendors.jpg            # Vendor menu background
    ├── food.jpg               # Food category background
    ├── Breakfast.jpg          # Breakfast category image
    ├── Rice Items.jpg         # Rice items category image
    ├── Curries.jpg            # Curries category image
    ├── Snacks.jpg             # Snacks category image
    ├── Desserts.jpg           # Desserts category image
    └── Sweets.jpg             # Sweets category image
```

> ⚠️ All image files must be in the **same folder as `main.py`** for the app to run correctly.

---

## ⚙️ Installation & Setup

### Prerequisites

| Tool | Download |
|---|---|
| Python 3.x | https://www.python.org/downloads/ |
| Git | https://git-scm.com/ |

---

### Step 1 — Clone the Repository

```bash
git clone https://github.com/BRUNDAVANAMSUREKHA/Campus-Connect.git
cd Campus-Connect
```

---

### Step 2 — Create Virtual Environment

```bash
python -m venv venv

# Windows
venv\Scripts\activate

# Mac / Linux
source venv/bin/activate
```

---

### Step 3 — Install Dependencies

```bash
pip install pillow
```

> ✅ `tkinter` comes **built into Python** — no separate install needed.

---

### Step 4 — Run the App

```bash
python main.py
```

---

## 🖥️ Usage Guide

### 1. Login
- Enter your KLU email: `yourname@klu.ac.in`
- Enter any password
- Click **Login**

### 2. Book Transport
- Click the **Transportation** button
- Select **Ambulance** or **Electric Vehicle**
- Type your **Source** and **Destination**
- Click **Book Vehicle** → confirmation popup appears

### 3. Order Food
- Click the **Food Ordering** button
- Choose a canteen — **Nalabagam**, **Sudexo**, or **Northern Canteen**
- Select a food category — Breakfast, Rice Items, Curries etc.
- Browse items and click **Order [item]** → confirmation popup appears

---

## 🔭 Roadmap

```
v1.0  ✅  KLU email login
v1.1  ✅  Transport booking (Ambulance + EV)
v1.2  ✅  Food ordering from 3 canteens
v1.3  ✅  Image-based graphical interface
v2.0  🚧  Database integration for order history
v2.1  📅  Real-time vehicle tracking
v2.2  📅  Online payment integration
v2.3  📅  Push notifications for order status
v3.0  📅  Mobile app version
```

---

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
   ```bash
   git checkout -b feature/your-feature
   ```
3. Commit and push
   ```bash
   git commit -m "Add: your feature"
   git push origin feature/your-feature
   ```
4. Open a Pull Request

---

## 👩‍💻 Author

<div align="center">

**Surekha Brundavanam**

[![GitHub](https://img.shields.io/badge/GitHub-BRUNDAVANAMSUREKHA-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/BRUNDAVANAMSUREKHA)

</div>

---

## 📄 License

⚠️ **Proprietary License** — All rights reserved © 2025 **Surekha Brundavanam**

This project and its source code may **not** be used, copied, modified, merged, published, distributed, sublicensed, or sold without explicit written permission from the author.

---

<div align="center">

**🎓 Campus Connect — Simplifying Campus Life at KLU**

*If this project helped you, consider giving it a ⭐ on GitHub!*

</div>
