# My Understanding for html, tailwind css and responsive code

## 01 เริ่มจากการเตรียมไฟล์ และ Layout หลักครับ
- เริ่มจากเตรียมไฟล์ images videos เข้ามาในโปรเจค
- เริ่มมอง Layout ภาพใหญ่ โดยเริ่มจากเขียนชื่อแต่ละ header, section และ footer ครับ

## 02 header
- เขียน nav และใส่โลโก้ และข้อความเมนูหลัก
- แล้วเริ่มแต่งด้วย tailwind css
- แยก col ซ้าย-ขวา ด้วย flex ครับ
- และตกแต่ง space height gap
- display hidden / inline แยกระหว่างมือถือกับคอม ตามที่กำหนด

## 03 banner
- เขียน col สำหรับแยก ซ้าย-ขวา
- แล้วใส่ข้อมูล/รูปให้ครบ
- ตกแต่งpadding/margin/bg/color/fontsize สำหรับมือถือก่อน
- แยก col ซ้าย-ขวา ด้วย flex สำหรับขนาดคอมพิวเตอร์ด้วย md:
- ตกแต่งpadding/margin/bg/color/fontsize สำหรับคอมพิวเตอร์

## 04 information
- เขียน col สำหรับแยก ซ้าย-ขวา
- แล้วใส่ข้อมูล/รูปให้ครบ
- แยก col ซ้าย-ขวา ด้วย flex สำหรับขนาดคอมพิวเตอร์ด้วย md:
- จัดการ main col layout ด้านซ้ายด้วย hidden md:block
- ตกแต่งpadding/margin/bg/color/fontsize สำหรับมือถือก่อน
- กำหนด width ของแต่ละ col ซ้าย-ขวา และ col ด้านในของด้านขวา
- ตกแต่งpadding/margin/bg/color/fontsize สำหรับคอมพิวเตอร์