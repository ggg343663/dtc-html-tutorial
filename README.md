# 📘 DTC HTML Tutorial – ห้องเรียน HTML/JS สำหรับ Ggg Aug (by ChatGPT)

> **เรียนโค้ดเว็บจากศูนย์ สู่โค้ดจริง!**  
> เรียนรู้โครงสร้างเว็บและการทำงาน JavaScript เบื้องต้น – ผ่านตัวอย่างจริงระบบ DTC QR Book  
> ถาม-ตอบ-แก้ไขโค้ดกับ ChatGPT ได้ทุกบท

---

## 🎯 จุดประสงค์

- สอน HTML, CSS, JavaScript ด้วยตัวอย่างจริง (DTC QR Book)
- เรียนโค้ดเว็บแบบ "จับมือทำ" เข้าใจทีละ step
- เหมาะกับผู้เริ่มต้น-ไม่มีพื้นฐาน
- สามารถถาม-ตอบ-ขออธิบายโค้ดแต่ละบทกับ ChatGPT ได้ตลอดเวลา
- นำไปต่อยอดระบบ DTC, เว็บแอป, หรือฝึกทำงานสาย Dev ได้จริง

---

## 🗂 โครงสร้างบทเรียน

| บท | หัวข้อ | ตัวอย่างไฟล์ |
|----|--------------------------|------------------------------|
| 1  | โครงสร้าง HTML & Hello World | 00_basic_html/basic_hello.html |
| 2  | สร้างฟอร์มรับข้อมูล (Password+PIN) | 01_form_input/password_pin_form.html |
| 3  | สร้างแถบแสดงความแข็งแรงรหัสผ่าน | 02_password_strength/password_strength.html |
| 4  | สร้าง Public Key จาก Password+PIN | 03_generate_key/generate_key.html |
| 5  | สร้าง QR Hash จาก Public Key | 04_generate_qr/generate_qr.html |
| 6  | การเชื่อมโยงข้ามหน้า (localStorage, Routing) | 05_register_qr/register_qr.html |
| 7  | ตัวอย่างระบบ DTC (Demo จริง) | 99_examples/dtc_full_example.html |

> *ไฟล์ทุกบทอยู่ในโฟลเดอร์เดียวกับ repo นี้  
> สามารถเปิดใน browser ได้ทันที  
> (แนะนำเรียนแบบ step-by-step จะเข้าใจง่ายสุด)*

---

## 🚦 วิธีใช้งาน / วิธีเรียน

1. Clone repo หรือดาวน์โหลดไฟล์ลงเครื่อง  
2. เปิดไฟล์แต่ละบทด้วย browser (แนะนำ Google Chrome, Edge, Firefox)
3. อ่าน comment/อธิบายในไฟล์ พร้อมทดลองแก้ไขโค้ด
4. ถาม-ตอบโค้ดแต่ละบทกับ ChatGPT (หรือส่งโค้ดมาให้ช่วยอธิบาย/แก้ไขได้ตลอด)
5. มี "โจทย์ท้าทาย" เล็ก ๆ ในแต่ละบท – ฝึกคิดแก้ไขต่อยอด

---

## 💡 เหมาะสำหรับใคร

- ผู้เริ่มต้น (ไม่ต้องมีพื้นฐานเขียนเว็บ)
- ผู้ที่ต้องการฝึกสร้างโปรเจกต์ HTML+JS แบบเห็นผลจริง
- ผู้ที่ต้องการเรียนรู้เทคนิคเว็บที่ใช้งานในโปรเจกต์ DTC QR Book
- สาย Coach/AI Coach หรือเรียนกับ ChatGPT แบบ Q&A

---

## 🌱 ตัวอย่างบทเรียน

### บทที่ 1: Hello HTML

```html
<!DOCTYPE html>
<html lang="th">
<head>
  <meta charset="UTF-8">
  <title>บทที่ 1 – Hello HTML</title>
</head>
<body>
  <h1>ยินดีต้อนรับสู่ห้องเรียน HTML</h1>
  <p>HTML (HyperText Markup Language) คือ ภาษาหลักสำหรับสร้างเว็บไซต์</p>
</body>
</html>
