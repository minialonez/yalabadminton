# 🏸 YALA BADMINTON — Club Management System

ระบบจัดการสนามแบดมินตัน Yala Badminton Club

## ✨ Features

- 🔐 **ระบบ Login** — Admin & สมาชิก พร้อม Fade-out animation
- 📷 **เช็คอินด้วยใบหน้า** — สแกนใบหน้าภายในรัศมีสนาม
- 📊 **Dashboard** — ดูสถานะผู้เล่นแบบ real-time (ว่าง / กำลังเล่น)
- 🎯 **สร้าง Party** — เชิญผู้เล่นที่ว่าง ครบ 4 คน เข้าคิวอัตโนมัติ
- 🏸 **จัดการ Court** — Warmup 5 นาที → Set 1 → พัก → Set 2 → สรุปผล
- 📋 **ระบบคิว** — อัตโนมัติ เมื่อคอร์ดว่างดึงคิวถัดไปเข้า
- 🔔 **Notification** — แจ้งเตือนทุกเหตุการณ์
- 📜 **ประวัติ** — บันทึกผลทุกเกม เวลาทุก set
- 👥 **จัดการสมาชิก** — เพิ่ม/ดู สมาชิก (Admin)
- 💾 **Persistent Storage** — ข้อมูลไม่หายเมื่อปิดหน้าเว็บ

## 🚀 Deploy to GitHub Pages

1. Push โค้ดนี้ขึ้น GitHub repository
2. ไปที่ **Settings → Pages**
3. เลือก Branch: `main`, Folder: `/ (root)`
4. กด **Save** → รอ 1-2 นาที
5. เข้าใช้งานที่ `https://your-username.github.io/yala-badminton/`

## 🔑 Login

| Role | Username | Password |
|------|----------|----------|
| Admin | `009` | `bxkssnrz` |
| สมาชิก | `YB-001` ~ `YB-008` | *(ไม่ต้องใส่ password)* |

## 📁 Project Structure

```
yala-badminton/
├── index.html          # Main application
├── css/
│   └── style.css       # Styles & animations
├── js/
│   └── app.js          # Application logic
├── assets/
│   └── (player photos)
└── README.md
```

## 🛠 Tech Stack

- HTML5 / CSS3 / Vanilla JavaScript
- LocalStorage for data persistence
- No build tools required — just open `index.html`

## 📜 License

MIT — Yala Badminton Club
