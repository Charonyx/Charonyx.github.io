# GitHub กับ Command Line

1. สร้าง repository ใน GitHub
2. สร้าง project ขึ้นมาในเครื่อง
3. อัปขึ้น GitHub โดยใข้ Command Line
    - เลือกตำแหน่ง Path ที่จะอัปขึ้น GitHub
    ```
    git init
    ```
    
    - อัปไฟล์ 
    ```
    git add .               // ไฟล์ทั้งหมด
    git add <<ชื่อไฟล์>>       // เฉพาะไฟล์
    ```

    - ตั้งชื่อ commit (commit คือคำอิบายใน GitHub)
    ```
    git commit -m "<<คำอธิบายในการอัปขึ้น GitHub>>"
    ```

    - remote เชือม repo บนเว็บ
    ```
    git remote add <<origin>> <<URL>>
    ```

    - push ขึ้น GitHub
    ```
    git push <<origin>> -u <<master>>
    ```

4. ไปเช็คว่าหน้า GitHub อัปเดตมั้ย