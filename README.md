# 🛒 Mini-Ecommerce - GitHub Workflow & Team Collaboration (Part 2)

โปรเจกต์นี้เป็นส่วนหนึ่งของ Lab วิชา Software Engineering โดยมีเป้าหมายเพื่อฝึกการทำงานร่วมกันบน GitHub ผ่านการใช้ GitHub Flow, Pull Request และการ Review โค้ด รวมถึงการจัดการกับ Merge Conflict

## 🎯 วัตถุประสงค์
- ฝึกใช้งาน Git commands และ workflow สำหรับทีม
- ใช้ Pull Request และ Code Review อย่างถูกต้อง
- แก้ไขและพัฒนาโปรเจกต์ Mini-Ecommerce ให้ดีขึ้น (จาก Version 1 → Version 2)

---

## 👨‍💻 ผู้พัฒนา
- **Dev A (Frontend/UX Developer)**: ปรับปรุง UI/UX, loading state, responsive layout
- **Dev B (Backend/Logic Developer)**: ปรับปรุงระบบค้นหา, เพิ่ม validation และแก้ไข merge conflict

---

## 🧱 โครงสร้างโปรเจกต์
mini-ecommerce/
├── index.html
├── js/
│ ├── main.js
│ └── products.json
├── css/
│ └── style.css
└── README.md

## 🚀 ฟีเจอร์ใหม่ใน Version 2

### ✅ โดย Dev A:
- เพิ่ม `Loading State` สำหรับการโหลดสินค้า
- ปรับปรุง UI ด้วย effect แบบ smooth hover (scale)
- จัด layout แบบ responsive (Flexbox)
- ปรับรูปสินค้าให้ใช้ลิงก์จริง (unsplash)
- แสดงราคาสินค้าด้วยเครื่องหมาย comma (เช่น 12,500 บาท)

### ✅ โดย Dev B:
- ปรับปรุงระบบค้นหาให้ตัด `whitespace` ก่อนค้นหา
- เพิ่ม validation: ถ้า input ว่าง ให้แสดงสินค้าทั้งหมด
- แก้ไขและจัดการ merge conflict ด้วย `git rebase`

## 🧪 การติดตั้งและใช้งาน

### 1. Clone Repository
```bash
git clone https://github.com/your-username/mini-ecommerce-collaboration.git
cd mini-ecommerce-collaboration
