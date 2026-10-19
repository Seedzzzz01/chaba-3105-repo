CHABA Repository สำหรับ 3105

Source:
https://raw.githubusercontent.com/Seedzzzz01/chaba-3105-repo/main/repo.json

รุ่นรายการ 1.64.1-commands.6 — CHABA Menu Studio
- หน้ากรอกคีย์สีถ่าน/มิ้นต์ พร้อมปุ่มวางและสถานะตรวจสอบ
- เมนูใหม่ สวิตช์เคลื่อนไหว กลุ่มพับได้ ปรับขนาด/ความทึบใน SETTING
- เปิดเมนูด้วย 3 นิ้วแตะจอ 2 ครั้ง ไม่มีปุ่มลอย กด × ปิดหน้าต่าง
- ระบบตรวจคีย์และฟังก์ชันเกมเดิมคงไว้ ใช้ RoV resources 1.64.1

อัปเดต:
1. ปิด RoV ให้สนิท แล้ว Restore แพตช์เดิม
2. 3105 > Sources > Refresh ให้เห็น commands.6 แล้วกด Download/Update
3. ใน Installed เลือก CHABA Menu Studio Auth 1.64.1 แล้ว Apply
4. เปิดเกม กรอกหรือวางคีย์ > ยืนยัน > รอตรวจ > ยืนยันผลสำเร็จ
5. ใช้ 3 นิ้วแตะจอ 2 ครั้งเปิดเมนู
หาก Source ยังเป็นรุ่นเก่า ลบเฉพาะ Source แล้วเพิ่ม URL นี้:
https://raw.githubusercontent.com/Seedzzzz01/chaba-3105-repo/main/repo.json?refresh=commands6
Refresh Source ไม่ Apply เกมให้อัตโนมัติ

ไฟล์ชุดนี้: CHABA_MenuStudio_AuthTheme_1.64.1.3105 ขนาด 270764 ไบต์
ช่วง iOS/iPadOS ใน Source: 17.0–18.7.10, 26.0–26.7 และ 27.0–27.2
ช่วง 27.0–27.2 จำกัด build ตาม repo.json รวม 24A446
ตัวแอป 3105 ยังต้องรองรับอุปกรณ์นั้นด้วย

ผ่านแบบจำลอง UI/ระบบคีย์ และตรวจซองแพ็กเกจ AES-GCM/SHA-256
ยังไม่ได้ทดสอบ Unity คีย์บอร์ด และการวางข้อความใน RoV บน iPhone จริง
หากสร้างหน้าคีย์ใหม่ไม่ได้ จะคืนหน้ากรอกเดิมเพื่อให้ตรวจคีย์ต่อได้
แพ็กเกจเก่าทั้ง Commands และ Gesture ยังเก็บใน packages/ สำหรับย้อนกลับ
ไฟล์ตั้งค่าบัญชี log และข้อมูลอุปกรณ์ไม่ได้เผยแพร่ใน repository นี้
