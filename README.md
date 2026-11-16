# SML Safety Hub

หน้าเมนูกลาง (static, ไฟล์เดียว) ไว้เข้าถึงระบบความปลอดภัยทั้ง 3 ระบบของ SML ในที่เดียว:

- **SHE Patrol** — https://hunnysri91021-sml.github.io/SHE-Patrol/
- **Work Permit** — https://hunnysri91021-sml.github.io/Safety-WorkPermit/
- **FireCheck** — https://firecheck.pages.dev/

หน้านี้เป็นแค่ลิงก์ ไม่มี backend/ไม่เก็บข้อมูลอะไรเอง — ทั้ง 3 ระบบยังแยกฐานข้อมูล/บัญชีผู้ใช้/การ
deploy ของตัวเองเหมือนเดิมทุกประการ ไม่ได้ถูกรวมเป็นระบบเดียวกัน

## วิธีอัปเดต

แก้ `index.html` แล้ว push เข้า `main` — ถ้าเปิด GitHub Pages ไว้แล้ว เว็บจะอัปเดตเองภายในไม่กี่นาที

## ถ้าเพิ่ม/เปลี่ยนระบบในอนาคต

แก้ลิงก์ในการ์ดที่ `index.html` ตรงๆ (ค้นหา `href="https://`) — ไม่มีการตั้งค่าอื่นให้แก้
