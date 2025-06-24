# Change SO Interface
change request
- interface ที่ใช้แก้ไข SO
* S : ด้วยข้อจำกัดด้าน license ผู้ใช้ต้องการแก้ไขข้อมูลใน SO เพิ่มโดยไม่ผ่าน SAP
* T : แก้ไข SAP interface ที่ใช้แก้ไข SO
* A
  - review การทำงานของ code
  - ออกแบบและหา case ที่ใช้ในการเพิ่ม field ใน SO
  - แก้ไข Code และทดสอบ
  - ทดสอบกับผู้เกี่ยวกับข้อง
* R : ผู้ใช้สามารถแก่ไข SO ได้ตาม field ที่ร้องขอมา
## องค์ประกอบ
- ZFM_SD_0018_SO_INTERFACE : main programe
- LZFG_SD_18TOP : ประกาศตัวแปร , พารามิเตอร์ และหน้า screen
- LZFG_SD_18F01 : ฟังก์ชันเพิ่มเติมที่เขียนขึ้นเพื่อให้ main ใช้
## จุดเด่น
- ใช้ STD BAPI สำหรับแก้ SO : BAPI_SALESORDER_CHANGE
