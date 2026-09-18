# 💰 Expense Tracker - บันทึกรายจ่าย

Web app ส่วนตัวสำหรับบันทึกรายจ่าย พร้อมอ่านสลิปโอนเงินอัตโนมัติด้วย OCR

## Features
- 📸 อัปโหลดสลิปโอนเงิน → อ่านจำนวนเงิน + วันที่อัตโนมัติ (OCR)
- 🏷️ 12 หมวดหมู่ (อาหาร/เดินทาง/ช้อปปิ้ง/บิล/...)
- 📊 สรุปรายวัน / สัปดาห์ / เดือน / ปี พร้อม chart
- 📥 Export เป็น CSV (UTF-8, เปิดใน Excel ได้)
- 🔒 **ข้อมูลอยู่ในเครื่องคุณเท่านั้น** (localStorage) — ไม่ผ่าน server, ไม่ track
- 📱 ติดตั้งเป็น PWA ได้ — ใช้ได้ทั้ง PC และมือถือ

## Tech
- Pure HTML/CSS/JS (no framework)
- Tesseract.js for OCR
- Service Worker for offline
- localStorage for data

## Deployment
Deploys as static site on Vercel. See `vercel.json`.

## Privacy
- ไม่มี server-side storage
- ไม่มี tracking / analytics
- ไม่มี external API ยกเว้น Tesseract.js CDN (open source OCR)