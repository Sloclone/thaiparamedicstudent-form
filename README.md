
# Thai Paramedic Student Form

ระบบบันทึกข้อมูลสมาชิก พร้อมอัปโหลดภาพถ่าย และส่งข้อมูลไปยัง Google Apps Script สำหรับจัดเก็บลง Google Sheets และสร้าง PDF รายบุคคล

## วิธีใช้งาน
1. แก้ไขไฟล์ `index.html` โดยใส่ URL จาก Apps Script ที่คุณ deploy แล้วใน `fetch("...")`
2. อัปโหลดไปยัง GitHub Pages พร้อม `.nojekyll`
3. ตรวจสอบที่ Google Sheet และ Drive

หากต้องการ deploy Google Script ให้ดูฟังก์ชัน `doPost(e)` ที่รองรับ `photo_base64` และข้อมูลสมาชิก
