# Technical Terms Saver Extension

Extension ที่ช่วยให้สามารถบันทึกและจัดการคำศัพท์ทางเทคนิคที่เกี่ยวข้องกับการเขียนโปรแกรม คำศัพท์และความหมายจะถูกส่งไปยัง API เพื่อเก็บข้อมูลในฐานข้อมูล MySQL

## การติดตั้ง

1. **โคลน Repository:**

   ```bash
   git clone https://github.com/aeff60/technical-terms-saver-extension.git
   cd technical-terms-saver-extension
   ```

2. **โหลด Extension เข้าไปใน Microsoft Edge:**

   - เปิด Edge และไปที่ `edge://extensions/`
   - เปิดใช้งาน "Developer mode" ถ้ายังไม่ได้เปิด
   - คลิกที่ "Load unpacked" และเลือกไดเรกทอรีที่โคลน repository มา

3. **รัน API :**
   - อันนี้ต้องเขียน API เองนะจ๊ะ

## ไฟล์

- **manifest.json**: ไฟล์การกำหนดค่าสำหรับ Extension
- **popup.html**: ไฟล์ HTML สำหรับอินเตอร์เฟซของ Extension
- **popup.js**: ไฟล์ JavaScript สำหรับจัดการฟังก์ชันการทำงานของ popup

## การพัฒนา

หากต้องการแก้ไข Extension ให้แก้ไขไฟล์และโหลด Extension ขึ้นมาบน Edge ใหม่
