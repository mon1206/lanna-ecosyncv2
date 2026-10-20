# Lanna EcoSync — GitHub Pages demo

ไฟล์ที่ต้องอัปโหลดเข้า GitHub repository:
- `index.html` (จำเป็น; หน้าเว็บพร้อมรูปและสคริปต์ในไฟล์เดียว)
- `.nojekyll` (ทางเลือก; ป้องกัน Jekyll แทรกแซง)

## วิธีเผยแพร่

1. สร้าง GitHub repository แบบ **Public** ชื่อ `lanna-ecosync`.
2. อัปโหลด **ไฟล์ `index.html`** ที่ root ของ repository (อย่าอัปโหลด ZIP โดยตรง).
3. ไปที่ **Settings → Pages → Build and deployment**.
4. เลือก **Deploy from a branch**, `main`, `/ (root)` แล้วกด **Save**.
5. รอเว็บไซต์เผยแพร่ (อาจใช้เวลาหลายนาที) แล้วเปิด `https://USERNAME.github.io/lanna-ecosync/` โดยเปลี่ยน `USERNAME` เป็นชื่อ GitHub ของคุณ.

## คำเตือน
เว็บไซต์นี้เป็นต้นแบบฝั่งเบราว์เซอร์ (`localStorage`) ไม่มีระบบล็อกอิน/ฐานข้อมูลกลางที่ปลอดภัย ข้อมูลและคิวจองไม่ซิงก์ข้ามอุปกรณ์ ไม่ควรใส่ข้อมูลส่วนตัวจริงหรือข้อมูลลูกค้า และไม่ควรถือเป็นระบบจองหรือจัดการสต็อกสำหรับใช้งานจริง
