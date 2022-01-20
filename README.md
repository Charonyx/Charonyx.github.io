# GitHub กับ Command Line

1. สร้าง repository ใน GitHub
2. สร้าง project ขึ้นมาในเครื่อง
3. อัปขึ้น GitHub โดยใข้ Command Line
    - เลือกตำแหน่ง Path ที่จะอัปขึ้น GitHub
    <code>git init</code>
    - อัปไฟล์ 
    <code>git add .          // ไฟล์ทั้งหมด</code>
    <code>git add <<ชื่อไฟล์>> // เฉพาะไฟล์</code>
    - ตั้งชื่อ commit (commit คือคำอิบายใน GitHub)
    <code>git commit -m "<<คำอธิบายในการอัปขึ้น GitHub>>"</code>
    - remote เชือม repo บนเว็บ
    <code>git remote add <<origin>> <<URL>></code>
    - push ขึ้น GitHub
    <code>git push <<origin>> -u <<master>></code>

4. ไปเช็คว่าหน้า GitHub อัปเดตมั้ย