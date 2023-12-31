# รายการตรวจสอบการป้องกันกำลังดิจิทัล
**หมายเหตุ:** _รายการตรวจสอบนี้มีไว้สำหรับผู้ชมทั่วไป ไม่เน้นไปที่พื้นที่หรือความต้องการใดๆ อย่างเฉพาะเจาะจง มีการออกแบบให้รวมเฉพาะการดำเนินการที่สามารถทำได้ด้วยการค้นหา Google ขั้นต่ำ และไม่ได้ครอบคลุมทุกสิ่ง_

## สิ่งที่ควรทำ

- [ ] ใช้รหัสผ่านยาว:
      - รหัสผ่านของบัญชีทั้งหมดควรเป็นรหัสผ่านที่สร้างขึ้นโดยผู้จัดการรหัสผ่าน มีความยาว 22 ตัวอักษรขึ้นไป ประกอบด้วยตัวพิมพ์ใหญ่, ตัวพิมพ์เล็ก, ตัวเลข และสัญลักษณ์
      ความยาวเป็นสิ่งสำคัญที่สุด!
- [ ] เลือกไม่รับโฆษณา "แบบปรับแต่ง":
      - ปิดการใช้งาน "ID โฆษณา" บนอุปกรณ์ทั้งหมด
- [ ] ปิด WIFI และ Bluetooth เมื่อไม่ได้ใช้งานโดยตรง
- [ ] ใช้การตรวจสอบสิทธิ์หลายปัจจัยเสมอ:
      - มักพบในการตั้งค่าบัญชีภายใต้ "ความเป็นส่วนตัวและความปลอดภัย"
      - การใช้ SMS เป็นวิธีที่ไม่ปลอดภัยที่สุด
- [ ] ค้นหาข้อมูลตัวเองและครอบครัวใน Google:
      - ขอลบภาพหรือข้อมูลที่จำเป็น [แบบฟอร์ม/แจ้งการลบตาม DMCA](https://github.com/irregularchat/public-resources/blob/main/Templates/DMCA%20Takedown%20Notice.md)
      - ปรับปรุงการตั้งค่าความเป็นส่วนตัวของบัญชีตามความจำเป็น

## สิ่งที่ไม่ควรทำ

- [ ] อย่าใช้รหัสผ่านเดียวกันซ้ำ:
      - รหัสผ่านที่ถูกแฮ็กถูกขายและเสนอฟรีบนเว็บมืด แม้ว่าคุณจะเก็บรหัสผ่านของคุณไว้อย่างปลอดภัย บริษัทอาจถูกแฮ็กได้
- [ ] อย่าเขียนรหัสผ่านลงบนกระดาษโดยเปิดเผย:
      - ใช้ผู้จัดการรหัสผ่านที่มีการเข้ารหัสแบบ end-to-end เพื่อเก็บรหัสผ่าน, พิน และคอมบิเนชัน
      - ใช้แชทที่เข้ารหัสและหายไปโดยอัตโนมัติอย่างน้อยในการแชร์คอมบิเนชันหรือพิน
- [ ] อย่าตั้งค่าความเป็นส่วนตัวเป็น "ทั้งหมด", "สาธารณะ" หรือ "ทุกคน":
      - พิจารณากรณีศึกษาของ Strava จำกัดโพสต์และโปรไฟล์เป็น "เฉพาะกับเพื่อน" หรือ "เฉพาะกับตัวเอง"
- [ ] อย่าใช้ SMS:
      - ใช้ Signal หรือ Element Messenger
      - ตั้งค่าให้แชทของคุณหายไปโดยอัตโนมัติเป็นค่าเริ่มต้น

## รายการตรวจสอบ

- [ ] ใช้ผู้จัดการรหัสผ่านเช่น Bitwarden
- [ ] เปิดใช้งานการอัปเดตอัตโนมัติ
- [ ] ปิดการใช้งาน "โฆษณาแบบปรับแต่ง" หรือ AD ID
      - ใช้โปรแกรมบล็อกโฆษณา
- [ ] เปิดใช้งานการตรวจสอบสิทธิ์หลายปัจจัย: [wiki MFA](https://wiki.irregularchat.com/en/resources/guides/dfp-guide/mfa-guide)
      - ใช้แอปพลิเคชัน Authenticator หรือ Yubikey แบบกายภาพ
- [ ] ใช้ VPN เสมอ เช่น MullvadVPN
- [ ] ปิดการเชื่อมต่อ WIFI อัตโนมัติ
- [ ] ล้างการเชื่อมต่อ WIFI & Bluetooth ที่ไม่ได้ใช้
- [ ] ทำและรักษาการสำรองข้อมูล:
      - เก็บไฟล์สำคัญไว้ในรูปแบบการสำรองข้อมูลแบบออฟไลน์
- [ ] เลือกไม่รับการเก็บข้อมูล:
      - https://simpleoptout.com/
- [ ] ค้นหาตัวเองใน Google
      - [การแจ้งการลบข้อมูลตาม DMCA](https://github.com/irregularchat/public-resources/blob/main/Templates/DMCA%20Takedown%20Notice.md) และการลบเนื้อหาส่วนตัว
- [ ] ถอนการติดตั้งแอปพลิเคชันที่ไม่ได้ใช้งานหรือไม่รู้จัก
- [ ] สร้างและใช้บัญชีที่ไม่ใช่บัญชีผู้ดูแลระบบ
- [ ] ล็อคอุปกรณ์ด้วย PIN 8 หลักหรือรหัสผ่านแบบข้อความ
      - อย่าใช้ตัวเลือกทางชีวภาพ

## ข้อแนะนำพิเศษ
- ใช้ VPN ในการดาวน์โหลดไฟล์และเมื่อคลิกลิงก์ที่น่าสงสัย - https://www.youtube.com/watch?v=wX75Z-4MEoM/
- แบบทดสอบภัยคุกคามฟิชชิงจาก Google - https://phishingquiz.withgoogle.com/
