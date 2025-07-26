# Portfolio Website - React Demo

เว็บไซต์ Portfolio ส่วนบุคคลที่ทันสมัยและสวยงาม สร้างด้วย React และ Vite พร้อมเอฟเฟกต์แอนิเมชันและการโต้ตอบที่น่าประทับใจ เหมาะสำหรับการแสดงผลงาน ทักษะ และประสบการณ์

## ✨ ฟีเจอร์หลัก

### 🎯 ส่วนประกอบหลัก
- **Navbar** - เมนูนำทางที่ใช้งานง่าย
- **Hero Section** - ส่วนแนะนำตัวที่โดดเด่น
- **Skills** - แสดงทักษะและความเชี่ยวชาญ
- **Services** - บริการที่ให้ได้
- **Portfolio** - แกลเลอรี่ผลงาน
- **Numbers** - สถิติและตัวเลขที่น่าประทับใจ
- **Testimonials** - คำรับรองจากลูกค้า
- **Contact** - ช่องทางการติดต่อ
- **Footer** - ข้อมูลท้ายเว็บไซต์

### 🎨 เอฟเฟกต์พิเศษ
- **Animated Cursor** - เคอร์เซอร์แอนิเมชันแบบกำหนดเอง
- **Count Up Animation** - ตัวเลขที่นับขึ้นแบบแอนิเมชั่น
- **Type Animation** - เอฟเฟกต์การพิมพ์ข้อความ
- **Parallax Tilt** - เอฟเฟกต์การเอียงตามการเลื่อนเมาส์
- **Visibility Sensor** - เอฟเฟกต์เมื่อเลื่อนหน้าจอ

## 🛠️ เทคโนโลยีที่ใช้

### Core Technologies
- **React** (v18.2.0) - ไลบรารี Frontend
- **Vite** (v7.0.0) - เครื่องมือ Build และเซิร์ฟเวอร์พัฒนา
- **ESLint** - เครื่องมือตรวจสอบคุณภาพโค้ด

### Animation & Effects Libraries
- **react-animated-cursor** (v2.11.2) - เคอร์เซอร์แอนิเมชัน
- **react-countup** (v6.5.0) - เอฟเฟกต์การนับตัวเลข
- **react-type-animation** (v3.2.0) - เอฟเฟกต์การพิมพ์
- **react-parallax-tilt** (v1.7.175) - เอฟเฟกต์ Parallax
- **react-visibility-sensor** (v5.1.1) - ตรวจจับการมองเห็น

### Icons & UI
- **react-icons** (v4.12.0) - ไอคอนหลากหลาย

## 📁 โครงสร้างโปรเจกต์

```
portfolio-website/
├── public/
│   └── vite.svg
├── src/
│   ├── assets/
│   │   └── react.svg
│   ├── components/
│   │   ├── Navbar/
│   │   │   └── Navbar.jsx
│   │   ├── Hero/
│   │   │   └── Hero.jsx
│   │   ├── Skills/
│   │   │   └── Skills.jsx
│   │   ├── Services/
│   │   │   └── Services.jsx
│   │   ├── Portfolio/
│   │   │   └── Portfolio.jsx
│   │   ├── Number/
│   │   │   └── Number.jsx
│   │   ├── Testimonials/
│   │   │   └── Testimonials.jsx
│   │   ├── Contact/
│   │   │   └── Contact.jsx
│   │   └── Footer/
│   │       └── Footer.jsx
│   ├── App.jsx
│   ├── App.css
│   ├── index.css
│   └── main.jsx
├── index.html
├── package.json
├── vite.config.js
└── README.md
```

## 🚀 การเริ่มต้นใช้งาน

### ข้อกำหนดเบื้องต้น

ตรวจสอบให้แน่ใจว่าคุณได้ติดตั้ง Node.js บนเครื่องของคุณแล้ว (เวอร์ชัน 16.0 ขึ้นไป)

### การติดตั้ง

1. คลอนโค้ดจาก repository:
```bash
git clone <repository-url>
cd portfolio-website
```

2. ติดตั้ง dependencies:
```bash
npm install
```

3. เริ่มเซิร์ฟเวอร์พัฒนา:
```bash
npm run dev
```

4. เปิดเบราว์เซอร์และไปที่ `http://localhost:5173`

### คำสั่งที่ใช้ได้

- `npm run dev` - เริ่มเซิร์ฟเวอร์พัฒนา
- `npm run build` - สร้างไฟล์สำหรับ production
- `npm run lint` - ตรวจสอบคุณภาพโค้ดด้วย ESLint
- `npm run preview` - ดูตัวอย่าง production build

## 🎯 ส่วนประกอบแต่ละส่วน

### Navbar Component
- เมนูนำทางแบบ sticky
- ลิงก์ไปยังส่วนต่างๆ ของเว็บไซต์
- รองรับการใช้งานบนมือถือ

### Hero Section
- ส่วนแนะนำตัวที่โดดเด่น
- เอฟเฟกต์การพิมพ์ข้อความ
- ปุ่ม Call-to-Action

### Skills Section
- แสดงทักษะและความเชี่ยวชาญ
- Progress bar หรือ icon แสดงระดับ
- หมวดหมู่ทักษะที่แตกต่างกัน

### Services Section
- บริการที่สามารถให้ได้
- การ์ดแสดงรายละเอียดบริการ
- ไอคอนประกอบแต่ละบริการ

### Portfolio Section
- แกลเลอรี่ผลงาน
- ภาพตัวอย่างและรายละเอียดโปรเจกต์
- ลิงก์ไปยังผลงานจริง

### Numbers Section
- สถิติและตัวเลขที่น่าประทับใจ
- เอฟเฟกต์การนับขึ้นแบบแอนิเมชั่น
- แสดงความสำเร็จและประสบการณ์

### Testimonials Section
- คำรับรองจากลูกค้าหรือเพื่อนร่วมงาน
- รูปภาพและคำบอกเล่า
- การเลื่อนแบบ carousel

### Contact Section
- ฟอร์มติดต่อ
- ข้อมูลการติดต่อ
- ลิงก์ไปยัง Social Media

### Footer
- ข้อมูลลิขสิทธิ์
- ลิงก์เพิ่มเติม
- Social media icons

## 🎨 ฟีเจอร์ดีไซน์

### Visual Effects
- **Gradient Background**: พื้นหลังไล่สีจากน้ำเงินอ่อนไปขาว
- **Animated Cursor**: เคอร์เซอร์แอนิเมชันที่ตอบสนองการคลิก
- **Smooth Scrolling**: การเลื่อนหน้าจอที่ลื่นไหล
- **Hover Effects**: เอฟเฟกต์เมื่อเมาส์อยู่เหนือองค์ประกอบ

### Responsive Design
- รองรับหน้าจอขนาด Desktop, Tablet, และ Mobile
- Font size ปรับตามขนาดหน้าจอ
- Layout ที่เหมาะสมกับอุปกรณ์ต่างๆ

### Typography
- ใช้ฟอนต์ 'Segoe UI' ที่อ่านง่าย
- ขนาดฟอนต์พื้นฐาน 18px (Desktop), 16px (Tablet), 15px (Mobile)
- Responsive typography ที่ปรับตามอุปกรณ์

## 🔧 การปรับแต่งและพัฒนาต่อ

### การเพิ่มเนื้อหา
- แก้ไขข้อมูลในแต่ละ Component
- เพิ่มรูปภาพในโฟลเดอร์ assets
- ปรับสีและสไตล์ในไฟล์ CSS

### การเพิ่มฟีเจอร์
- เพิ่ม Blog section
- เพิ่มระบบ Multi-language
- เพิ่ม Dark/Light mode
- เพิ่มระบบ CMS สำหรับจัดการเนื้อหา

### การปรับปรุง Performance
- Image optimization
- Code splitting
- Lazy loading
- CDN integration

## 📱 การรองรับอุปกรณ์

### Desktop (1200px+)
- Layout แบบเต็มความกว้าง
- เอฟเฟกต์แอนิเมชันครบถ้วน
- เคอร์เซอร์แอนิเมชัน

### Tablet (768px - 1199px)
- Layout ปรับให้เหมาะสมกับหน้าจอกลาง
- ขนาดฟอนต์ 16px
- เมนูแบบยุบได้

### Mobile (480px - 767px)
- Layout แบบ single column
- ขนาดฟอนต์ 15px
- เมนู hamburger
- Touch-friendly interface

## 🤝 การมีส่วนร่วม

1. Fork repository
2. สร้าง feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit การเปลี่ยนแปลง (`git commit -m 'Add some AmazingFeature'`)
4. Push ไปยัง branch (`git push origin feature/AmazingFeature`)
5. เปิด Pull Request


## 🎓 แนวคิดการพัฒนาที่แสดงให้เห็น

### React Best Practices
- **Component Architecture**: การแบ่งคอมโพเนนต์ที่มีหน้าที่ชัดเจน
- **Props Management**: การส่งข้อมูลระหว่างคอมโพเนนต์
- **State Management**: การจัดการสถานะแอปพลิเคชัน
- **Hooks Usage**: การใช้ React Hooks อย่างมีประสิทธิภาพ

### Modern Web Development
- **ES6+ Features**: Arrow functions, destructuring, modules
- **Build Tools**: Vite สำหรับการพัฒนาที่รวดเร็ว
- **Code Quality**: ESLint สำหรับมาตรฐานโค้ด
- **Package Management**: npm dependencies

### UI/UX Design Principles
- **User Experience**: การออกแบบที่เน้นผู้ใช้
- **Visual Hierarchy**: การจัดลำดับความสำคัญของข้อมูล
- **Interactive Design**: การตอบสนองของผู้ใช้
- **Accessibility**: การเข้าถึงได้สำหรับทุกคน

### Performance Optimization
- **Responsive Images**: รูปภาพที่ปรับตามหน้าจอ
- **Smooth Animations**: แอนิเมชันที่ไม่กระตุก
- **Code Organization**: การจัดระเบียบโค้ดที่ดี
- **Bundle Optimization**: การจัดการไฟล์ build

---
