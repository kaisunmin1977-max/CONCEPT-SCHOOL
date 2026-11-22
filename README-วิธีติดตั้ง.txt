# CONCEPT SCHOOL — ชุดติดตั้งไอคอน PWA

## ไฟล์ในชุดนี้
- `index.html` หน้าเริ่มต้นและปุ่มเปิดระบบ
- `manifest.webmanifest` ข้อมูลชื่อแอปและไอคอน
- `sw.js` แคชเฉพาะหน้าเริ่มต้นและไฟล์ไอคอน
- `icons/` ไอคอนหลายขนาดจากโลโก้ที่ผู้ใช้อัปโหลด

## วิธีเผยแพร่ด้วย GitHub Pages
1. เข้า GitHub แล้วสร้าง Repository ใหม่ ตั้งชื่อ `concept-school`.
2. เลือก Public และสร้าง Repository.
3. กด Add file > Upload files.
4. แตก ZIP นี้ในคอมพิวเตอร์ แล้วอัปโหลดไฟล์และโฟลเดอร์ทั้งหมดที่อยู่ข้างใน (ต้องเห็น `index.html` อยู่ระดับแรกของ Repository).
5. กด Commit changes.
6. เข้า Settings > Pages.
7. ในส่วน Build and deployment เลือก Deploy from a branch.
8. เลือก Branch `main` และ Folder `/ (root)` แล้วกด Save.
9. รอ GitHub แสดงลิงก์เว็บไซต์ เช่น `https://ชื่อบัญชี.github.io/concept-school/`.

## วิธีติดตั้งบน Android
1. เปิดลิงก์ GitHub Pages ด้วย Chrome.
2. แตะเมนู ⋮ แล้วเลือก Install app หรือ Add to Home screen.
3. ยืนยันติดตั้ง ไอคอน CONCEPT SCHOOL จะปรากฏบนหน้าจอ.

## วิธีติดตั้งบน iPhone / iPad
1. เปิดลิงก์ GitHub Pages ด้วย Safari.
2. แตะปุ่ม Share.
3. เลือก Add to Home Screen.
4. เปิดตัวเลือก Open as Web App (ถ้ามี) แล้วแตะ Add.

## หมายเหตุสำคัญ
- หน้าไอคอนนี้เป็นทางเข้าไปยัง Google Apps Script เดิม โดยกดปุ่ม “เปิดโปรแกรมเช็คชื่อ”.
- ไม่ได้แก้ไขโค้ดหรือข้อมูลใน Google Apps Script.
- ต้องเชื่อมต่ออินเทอร์เน็ตเพื่อใช้งานระบบเช็คชื่อ.
- การเข้าสู่ระบบและสิทธิ์การใช้งานยังเป็นไปตามการตั้งค่าของ Google Apps Script เดิม.
- ไอคอน PWA จะติดตั้งบนอุปกรณ์แต่ละเครื่องแยกกัน ไม่ได้ติดตั้งให้ทุกเครื่องอัตโนมัติ.
