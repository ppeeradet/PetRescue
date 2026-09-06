# Pet Rescue Mission

เกมคำศัพท์ภาษาอังกฤษและการออกเสียง ผ่านภารกิจกู้ภัยเพื่อนสัตว์

- Production: https://ppeeradet.github.io/PetRescue/
- Canonical production file: `index.html`
- Status: Active
- Architecture: static single-file HTML application

## Repository policy

- `index.html` คือ production version หลักเสมอ
- ไม่สร้าง `update.html` หรือสำเนา production เพิ่ม
- ใช้ Git history, tags และ releases สำหรับประวัติเวอร์ชัน
- Phase 1 เป็น metadata-only: ไม่แก้ gameplay หรือ `index.html`
- เก็บไฟล์ legacy ไว้ก่อนจนกว่าจะผ่านการ review

## Legacy HTML inventory

- `word_rescue_mission.html` — divergent legacy candidate; SHA-256 ต่างจาก `index.html` และต้อง review code ก่อน archive/delete

## Local use

เปิด `index.html` ในเว็บเบราว์เซอร์ หรือใช้ลิงก์ Production ด้านบน

