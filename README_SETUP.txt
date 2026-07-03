วิธีทำให้เว็บออนไลน์

1) เข้า Firebase Console แล้วสร้าง Project
2) สร้าง Web App แล้วคัดลอก firebaseConfig
3) เปิด Firestore Database > Create database > Start in test mode
4) เปิดไฟล์ index.html แล้วแทนค่า firebaseConfig ตรง PASTE_...
5) เปลี่ยน ADMIN_KEY = "CHANGE_ME_ADMIN_KEY" เป็นรหัสแอดมินของคุณ
6) อัปไฟล์ index.html ขึ้น GitHub Pages หรือ Netlify
7) ส่งลิงก์ให้เพื่อน ทุกคนจะเห็นข้อมูลเดียวกัน

หมายเหตุ:
- Firebase Config ไม่ใช่รหัสลับ สามารถอยู่ในหน้าเว็บได้
- Admin Key ใน HTML ล้วนยังถูก Inspect ดูได้ เหมาะกับการเล่นสนุก ๆ ในห้อง
- ถ้าต้องการปลอดภัยจริง ต้องเพิ่ม Firebase Auth/Cloud Functions
