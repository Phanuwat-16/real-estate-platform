# Real Estate Platform (แพลตฟอร์มฝากขาย-เช่า อสังหาริมทรัพย์)

![Status](https://img.shields.io/badge/status-active_development-blue?style=flat-square)
![License](https://img.shields.io/badge/license-MIT-green?style=flat-square)
![Platform](https://img.shields.io/badge/platform-web-orange?style=flat-square)

แพลตฟอร์มศูนย์รวมการลงประกาศ ฝากขาย และเช่า อสังหาริมทรัพย์ (บ้าน คอนโด ที่ดิน อาคารพาณิชย์) พร้อมระบบค้นหาและจัดการสำหรับผู้ซื้อ ผู้ขาย และนายหน้า

---

## 🌟 ฟีเจอร์หลัก (Key Features)

### 1. ระบบจัดการประกาศ (Listing Management)
- **ลงประกาศฝากขาย/เช่า:** อัปโหลดรูปภาพ รายละเอียด ขนาดพื้นที่ ราคา พิกัดทำเล
- **หมวดหมู่อสังหาริมทรัพย์:** บ้านเดี่ยว, คอนโดมิเนียม, ทาวน์โฮม, ที่ดิน, อาคารพาณิชย์
- **สถานะประกาศ:** เปิดขาย/เช่า, ติดจอง, ขายแล้ว

### 2. ระบบค้นหาและคัดกรอง (Search & Filter)
- ค้นหาตามทำเล/โซน (เช่น แนวรถไฟฟ้า, จังหวัด, เขต/อำเภอ)
- ตัวกรองตามช่วงราคา (Price Range)
- ตัวกรองจำนวนห้องนอน ห้องน้ำ ขนาดพื้นที่
- คัดกรองตามประเภท: ขาย หรือ ให้เช่า

### 3. ระบบสมาชิกและการติดต่อ (User & Inquiries)
- ระบบสมาชิก: ผู้ซื้อ (Buyer), ผู้ขาย/เจ้าของทรัพย์ (Owner), นายหน้า (Agent)
- แบบฟอร์มติดต่อสอบถาม / นัดดูสถานที่จริง
- ปุ่มเชื่อมต่อแชท (Line / WhatsApp / โทรศัพท์)

### 4. แดชบอร์ดผู้ดูแลและสถิติ (Admin & Analytics)
- จัดการและอนุมัติประกาศ
- ตรวจสอบสถิติผู้เข้าชมประกาศ (Page Views & Inquiries)

---

## 📁 โครงสร้างโปรเจกต์ (Project Structure)

```text
real-estate-platform/
├── .gitignore
├── README.md
└── ... (Source code)
```

---

## 🚀 การเริ่มต้นพัฒนา (Getting Started)

1. **Clone repository:**
   ```bash
   git clone <repository-url>
   cd real-estate-platform
   ```

## 🗺️ แผนการพัฒนา (Development Roadmap)

- [x] ออกแบบโครงสร้างและฟีเจอร์หลักของระบบ
- [x] สร้าง Git Repository และตั้งค่าโปรเจกต์เริ่มต้น
- [ ] พัฒนาแบบฟอร์มลงประกาศและระบบค้นหาอสังหาริมทรัพย์
- [ ] ติดตั้งระบบยืนยันตัวตนผู้ใช้ (Authentication & Authorization)
- [ ] พัฒนาระบบแชทติดต่อและนัดดูสถานที่
- [ ] ออกแบบ Dashboard สรุปสถิติสำหรับผู้ดูแลระบบ

---

## 📝 License
MIT License

