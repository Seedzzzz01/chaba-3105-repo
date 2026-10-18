CHABA Repository สำหรับ 3105

รายการนี้แจกแพ็กเกจ CHABA Commands + Changelog สำหรับเกม RoV resources 1.64.1
ต้องมีคีย์ CHABA ที่ยังใช้ได้ และแอป 3105 ที่รองรับอุปกรณ์ของผู้ใช้

เพิ่ม Source
ใน 3105 เปิด Sources > Add Source แล้วใส่ URL แบบ Raw ของ repo.json
รูปแบบ URL เมื่อเผยแพร่บน GitHub:
https://raw.githubusercontent.com/Seedzzzz01/chaba-3105-repo/main/repo.json
อย่าใช้ลิงก์หน้า github.com/.../blob/... เพราะลิงก์นั้นเป็นหน้าเว็บ ไม่ใช่ JSON โดยตรง

กด Refresh แล้วเลือก CHABA Menu 1.64.1 เพื่อดาวน์โหลด/นำเข้า
ปิด RoV ให้สนิทและ Restore แพตช์เก่าก่อน Apply ชุดใหม่
เปิดเกม ตรวจคีย์ และกดตกลงที่ประกาศผ่านคีย์ตามเดิม
การ Refresh Source จะอัปเดตรายการ ไม่ได้ Apply เกมให้อัตโนมัติ

อัปเดตครั้งนี้
- ย่อข้อความในแถบ CHANGELOG ของเกมให้ตรงกับ Source
- แก้ Source ที่ขึ้น Unsupported บน iOS/iPadOS 27.x โดยอนุญาตทุก build
- เปลี่ยนสกิน: เปิดแชตในแมตช์ พิมพ์ /skin 1 แล้วกดส่ง เลือกเลข 0–99 ได้
- คืนสกินเดิม: /skin reset ต้องมีทรัพยากรสกินพร้อม ใช้ตอนฮีโร่ยังมีชีวิต
- ปรับกล้อง: /cam 2.5 รับเลข 1–4 รวมทศนิยม คืนมุมมองเดิมด้วย /cam reset
- เอ็กคิ้วอัตโนมัติปรับเกณฑ์เลือดศัตรูเป็นต่ำกว่า 15%
- ปรับการอัปเดตคูลดาวน์ Talent และเพิ่มแถบ CHANGELOG ในเมนูเดิม

ไฟล์
repo.json คือ Source ที่เพิ่มในแอปโดยตรง
sources.json คือรายการ Source สำหรับระบบที่รองรับ source catalog
packages/ เก็บแพ็กเกจ .3105 ที่ JSON อ้างถึง
SHA-256 และขนาดไฟล์ใน repo.json ต้องตรงไฟล์จริงเสมอ

สำหรับผู้ดูแล
อัปเดตไฟล์แพ็กเกจ พร้อมเปลี่ยน version, download, sha256, size, publishedAt และ changelog
คง identifier เดิมของ repository และ package เพื่อให้เป็นรายการเดิมเมื่อ Refresh
supportedOS อนุญาต iPadOS 26.5 และ iOS/iPadOS 27.x ทุก build
เป็นการเปิดสิทธิ์ดาวน์โหลดใน Source ต้องใช้แอป 3105 ที่รองรับเครื่องนั้นด้วย
ยังไม่ได้ยืนยันการ Apply และการทำงานในเกมบน iOS/iPadOS 27 ทุกเวอร์ชัน
ฟังก์ชันใหม่ผ่านแบบจำลองและการตรวจไฟล์ แต่ยังรอผลทดสอบใน RoV บนอุปกรณ์จริง

เผยแพร่เฉพาะ repository JSON, README และแพ็กเกจแจกใช้งาน
config.local.json, log, ข้อมูลอุปกรณ์ และไฟล์ตั้งค่าบัญชีไม่ได้อยู่ใน repository นี้
