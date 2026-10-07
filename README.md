# Kru Noon Science Learning Hub

เว็บไซต์กลางสำหรับรวบรวมบทเรียน เกม และแบบทดสอบวิทยาศาสตร์
แยกเป็นระดับชั้น ม.1 และ ม.2

## เว็บไซต์ที่เชื่อมไว้แล้ว

### ม.1
- ศึกษาเซลล์: https://planooncell.netlify.app
- การสังเคราะห์ด้วยแสง: https://planoonlight.netlify.app

### ม.2
- กายวิภาคหัวใจ: https://planoon.my.canva.site/heart-anatomy-guide
- หน่วยไต: https://planoon.my.canva.site/kidney-anatomy-quiz

## วิธีใช้งาน

1. อัปโหลดไฟล์ทั้งหมดในโฟลเดอร์นี้ขึ้น GitHub Repository
2. เชื่อม Repository กับ Netlify
3. ตั้ง Publish directory เป็นโฟลเดอร์รากของโปรเจกต์
4. Deploy เว็บไซต์

## วิธีเพิ่มบทเรียนใหม่

คัดลอกการ์ด `<article class="lesson-card"> ... </article>`
ในไฟล์ `index.html` แล้วเปลี่ยน
- ไอคอน
- ชื่อเรื่อง
- คำอธิบาย
- ลิงก์

หากเป็นโครงการที่มีโค้ด HTML/CSS/JS ของตัวเอง
สามารถสร้างโฟลเดอร์เพิ่ม เช่น

```
m1/microscope/
m2/separation/
m2/resq-science/
```

แล้ววาง `index.html` ของโครงการไว้ในโฟลเดอร์นั้น
จากนั้นเปลี่ยนลิงก์ของการ์ดเป็น เช่น

```
m2/resq-science/
```
