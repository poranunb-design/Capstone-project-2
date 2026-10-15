# 🌐 NetFlow Monitoring in Enterprise Network

## 📌 เกี่ยวกับโปรเจกต์
โปรเจกต์จำลองระบบเครือข่ายองค์กรด้วย **Cisco Packet Tracer** เพื่อศึกษาการใช้ **NetFlow** ในการตรวจสอบทราฟฟิก วิเคราะห์การใช้งานเครือข่าย และเรียนรู้การวินิจฉัยปัญหา

## 🎯 วัตถุประสงค์
- ศึกษาการทำงานของ NetFlow Exporter และ Collector
- ตรวจสอบทราฟฟิก ICMP, HTTP และ DNS
- วิเคราะห์ Flow Record เช่น IP ต้นทาง/ปลายทาง พอร์ต โปรโตคอล และจำนวนแพ็กเก็ต
- ศึกษารูปแบบความผิดปกติและการแก้ไขปัญหาเครือข่าย

## 🛠️ เครื่องมือ
- Cisco Packet Tracer
- Router และ Switch
- NetFlow Collector
- PC และ Web/DNS Server จำลอง

## 🧪 การทดลอง
1. ทดสอบ Ping จาก PC ไปยัง Gateway และตรวจสอบ ICMP Flow
2. เปิดเว็บไซต์ผ่าน IP Address และ Domain Name เพื่อสังเกต HTTP/DNS Flow
3. เปรียบเทียบ Flow Record และสถิติการรับส่งข้อมูล
4. จำลองข้อผิดพลาดของ NetFlow และตรวจสอบการกู้คืนตาม Runbook

## 🚀 วิธีใช้งาน
1. เปิด `Capstone-project-2.pka` ด้วย Cisco Packet Tracer
2. เปิดบริการ **NetFlow Collector** ในแท็บ Desktop
3. สร้างทราฟฟิกด้วย Ping หรือ Web Browser จาก PC จำลอง
4. ตรวจสอบ Flow Record ใน Collector
5. ใช้ `Runbook.pdf` ประกอบการทดสอบและแก้ไขปัญหา

## 📂 เอกสารประกอบ
- `Capstone-project-2.pka` — ไฟล์กิจกรรม Packet Tracer
- `Lab 23.2.2.pdf` — ขั้นตอนการทดลอง NetFlow
- `Runbook.pdf` — แนวทางสาธิตและแก้ไขปัญหา
- `การปรับใช้ NetFlow ในเครือข่ายองค์กรจำลอง.pdf` — รายงานการศึกษา

> **หมายเหตุ:** Packet Tracer จำลอง NetFlow แบบพื้นฐาน และกรณีภัยคุกคามบางประเภทในรายงานเป็นการวิเคราะห์เชิงแนวคิด ไม่ใช่ผลทดสอบจริงทั้งหมด

