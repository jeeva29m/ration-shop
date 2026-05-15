# 🌾 Ration Shop Management System

> A web-based application to digitalize ration shop operations — built to replace manual paperwork with multi-role authentication, slot booking, and inventory management.

**🔗 Live Demo:** [jeeva29m.github.io/ration-shop](https://jeeva29m.github.io/ration-shop/)

![HTML](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=flat&logo=bootstrap&logoColor=white)

---

## 📖 About the Project

In India, ration shops under the Public Distribution System (PDS) serve millions of customers but still rely heavily on paper-based record keeping. This causes long queues, overcrowding, stock-out incidents, and inefficient distribution.

**Ration Shop Management System** is a web application that digitalizes the entire operation — from shop registration and inventory management to customer slot booking and daily sales tracking.

---

## ✨ Features

### 👤 Three User Roles

**🛠️ Admin Panel**
- Register new ration shops with location and capacity
- View all registered shops with low-stock alerts
- Manage customer registrations across all shops
- Monitor slot bookings system-wide

**👷 Employee Workstation**
- Upload and update product stock daily
- Record daily sales with multi-item bills
- View incoming customer slot bookings for the day
- Token-based queue management

**🧑 Customer Zone**
- Self-register with ration card details
- Book a distribution slot by date and hour (9 AM – 5 PM windows)
- View profile and active bookings
- Token generation on confirmed bookings

### 🎯 Core Capabilities
- 📦 Real-time stock monitoring with low-inventory flags
- 📅 Slot booking system to eliminate overcrowding
- 🧾 Daily sales entry with itemized bill generation
- 📱 Fully responsive UI — works on mobile, tablet, and desktop
- 🎟️ Token-based customer queue at the shop

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| **Frontend** | HTML5, CSS3, JavaScript (ES6+) |
| **UI Framework** | Bootstrap 5 |
| **State (current)** | Browser localStorage + in-memory |
| **Hosting** | GitHub Pages |
| **Backend (planned)** | Firebase Authentication + Firestore |

> **Note:** The current deployed version uses in-browser state for a working demo. A Firebase backend (Auth + Firestore) is being integrated next to support persistent multi-user data, real authentication, and live sync across devices.

---

## 🚀 Running Locally

```bash
# Clone the repo
git clone https://github.com/jeeva29m/ration-shop.git
cd ration-shop

# Open in browser (no build step needed)
open index.html
```

That's it — no installation, no dependencies. Static site.

---

## 📂 Project Structure

```
ration-shop/
├── index.html          # Main entry — all three role panels
├── style.css           # Custom styles on top of Bootstrap
├── script.js           # Application logic (auth, booking, stock)
└── assets/             # Icons and images
```

---

## 🗺️ Roadmap

- [x] Multi-role UI (Admin / Employee / Customer)
- [x] Shop registration and listing
- [x] Slot booking with date and hour selection
- [x] Daily sales entry with bill generation
- [x] Responsive design for mobile and desktop
- [ ] Firebase Authentication for real login
- [ ] Firestore for persistent data
- [ ] SMS notifications for slot confirmations
- [ ] Admin analytics dashboard
- [ ] Migration to React.js

---

## 💡 What I Learned

Building this project end-to-end taught me:
- How to structure a multi-role single-page application without a framework
- Designing for the lowest-common-denominator device (low-end Android in rural areas)
- The difference between "it works on my screen" and "it works for the user"
- Why every form needs validation, every action needs confirmation, and every error needs a clear message

---

## 👤 Author

**Jeevamuthu M**
M.Sc Computer Science | Government Arts College, Karur
- LinkedIn: [linkedin.com/in/jeevamuthu29](https://www.linkedin.com/in/jeevamuthu29/)
- GitHub: [@jeeva29m](https://github.com/jeeva29m)
- Email: jeevamuthu2911@gmail.com

---

## 📄 License

This project is open-sourced for educational purposes. Feel free to fork and adapt for your own learning.
