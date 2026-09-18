<div align="center">

# 💰 Expense Tracker

บันทึกรายจ่ายส่วนตัว พร้อม OCR อ่านสลิปอัตโนมัติ

## 🚀 Deploy บน Vercel (กดปุ่มเดียว)

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/jiradejwt-stack/expense-tracker&project-name=expense-tracker&repository-name=expense-tracker)

**ขั้นตอน:**
1. กดปุ่มข้างบน
2. Vercel จะถาม login (ใช้ GitHub account `jiradejwt-stack` ที่สมัครไว้)
3. กด **Deploy** → เสร็จ!
4. ได้ URL เช่น `https://expense-tracker-jiradejwt-stack.vercel.app`
5. เปิด URL ในมือถือ → เมนู → "Add to Home Screen" → ใช้ได้ทุกที่!

## หลัง Deploy

- ทุกครั้งที่ `git push` code ใหม่ → Vercel auto-deploy อัตโนมัติ
- Vercel จะให้ HTTPS ฟรี
- ไม่มีโฆษณา ไม่ track ไม่เก็บ data

## Features
- 📸 OCR อ่านสลิป (รองรับภาษาไทย + อังกฤษ)
- 🏷️ 12 categories ปรับแต่งได้
- 📊 Summary รายวัน/สัปดาห์/เดือน/ปี + chart
- 📥 Export CSV (เปิดใน Excel)
- 🔒 ข้อมูลใน localStorage เครื่องคุณเท่านั้น
- 📱 PWA — install เป็น app บนมือถือได้

## Tech
- Pure HTML/CSS/JS (no framework, no build step)
- Tesseract.js for OCR
- Service Worker for offline

## License
MIT
