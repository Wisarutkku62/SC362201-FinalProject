# โปรเจกต์รายวิชา Web Design Technology SC362201

# IT14 Cyberbully & Awareness
เว็บแอปพลิเคชันเพื่อการเรียนรู้และสร้างความตระหนักรู้ด้านความปลอดภัยทางไซเบอร์ (Cybersecurity Awareness Platform) พัฒนาด้วยเทคโนโลยี Frontend (HTML5, CSS3, JavaScript)

# จัดทำโดย
| รหัสนักศึกษา | ชื่อ-สกุล | สาขา | 
|---|---|---|
| 683380054-2 | นายวิศรุต เครือลุน | IT | 
| 683380042-9 | นายธนกฤต ใจสุข | IT | 


# ภาพรวมโครงงาน (Project Overview)
IT14-CyberAwareness เป็นโปรเจกต์เว็บแอปพลิเคชันสื่อการเรียนรู้ออนไลน์ที่มุ่งเน้นการเสริมสร้างทักษะและความเข้าใจเกี่ยวกับภัยคุกคามทางไซเบอร์ ตัวระบบออกแบบมาให้เข้าถึงง่าย น่าสนใจ และมีปฏิสัมพันธ์กับผู้ใช้ (Interactive) ผ่านบทเรียน มินิเกม สถานการณ์จำลอง และเครื่องมือประเมินความเสี่ยง

# ฟีเจอร์หลัก (Key Features)
## 1.คลังบทเรียนและความรู้ (Learning & Knowledge Base)
- Cyber Threats (cyberthreats.html): รวมข้อมูลและรูปแบบภัยคุกคามทางไซเบอร์ที่พบบ่อยในปัจจุบัน
- DailyCY (DailyCY.html): เกร็ดความรู้และข่าวสารภัยไซเบอร์รายวัน
- Parent Guide (parent.html): คู่มือการดูแลเด็กและเยาวชนให้ปลอดภัยบนโลกออนไลน์สำหรับผู้ปกครอง
- Cyber Skills & Guide PR (GuidePR.html): สื่อการเรียนรู้เพื่อสร้างทักษะการป้องกันตนเองและการประชาสัมพันธ์
  
## 2.เกมและแบบทดสอบเชิงโต้ตอบ (Interactive Games & Simulations)
- Decode Image Game (decodeimage.html): เกมถอดรหัสภาพและปริศนาไซเบอร์
- Matching Game (games.html): เกมจับคู่สัญลักษณ์ คำศัพท์ และความรู้ความปลอดภัยไซเบอร์
- Spot the Flag (spottheflag.html): เกมจับผิดสังเกตจุดเสี่ยงหรือธงภัยคุกคาม
- Fake App Simulation (fakeapp.html): สถานการณ์จำลองการตรวจสอบและสังเกตแอปพลิเคชันปลอม
- Face-to-Face & Roleplay (facetoface.html, roleplay.html): ระบบจำลองบทบาทสมมติในการรับมือเหตุการณ์ภัยไซเบอร์
  
## 3.การทดสอบและสถิติ (Testing & Statistics)
- Backtest & Test Readiness (Backtest.html): ระบบทดสอบประเมินระดับความตระหนักรู้และความพร้อมก่อน-หลังเรียนรู้
- Statistics Dashboard (statistic.html): สรุปสถิติผลการเรียนรู้และสถิติภัยไซเบอร์

## 4.ชุมชนและการให้คำปรึกษา (Community & Consult)
- Community Space (community.html): พื้นที่แลกเปลี่ยนประสบการณ์และความรู้ในกลุ่มผู้ใช้
- Consult Center (consult.html): ศูนย์ให้คำแนะนำเมื่อเจอปัญหาภัยคุกคามออนไลน์

## เทคโนโลยีที่ใช้ (Tech Stack)
- HTML5: ใช้จัดโครงสร้างหน้าเว็บแยกตามบทเรียน โมดูล และมินิเกมต่างๆ
- CSS3: ใช้จัดการสไตล์ UI/UX, เมนูการนำทางสำหรับมือถือ (css/mobile-nav.css) และธีมเฉพาะหน้า
- JavaScript: ใช้จัดการลอจิกมินิเกม สถานการณ์จำลอง และคำนวณผลการทดสอบแบบ Client-side
- SVG / PNG Assets: ภาพประกอบ กราฟิก และสื่อการเรียนรู้เชิงปฏิสัมพันธ์

## โครงสร้างไฟล์ในโปรเจกต์ (Project Structure)
```
IT14-CyberAwareness/
├── css/                        # ไฟล์สไตล์ CSS แยกตามโมดูลและหน้าเว็บ
│   ├── about.css
│   ├── Backtest.css
│   ├── community.css
│   ├── consult.css
│   ├── cyberthreats.css
│   ├── DailyCY.css
│   ├── decodeimage.css
│   ├── facetoface.css
│   ├── fakeapp.css
│   ├── games.css
│   ├── guide.css
│   ├── index.css
│   ├── knowledgebase.css
│   ├── learning.css
│   ├── lessons.css
│   ├── matchgame.css
│   ├── mobile-nav.css
│   ├── parent.css
│   ├── roleplay.css
│   ├── skills.css
│   ├── spottheflag.css
│   ├── spottheflagresult.css
│   ├── statistic.css
│   ├── Testready.css
│   └── translatecyber.css
├── images/                     # โฟลเดอร์เก็บรูปภาพ กราฟิก และไอคอนประกอบ
├── about.html                  # หน้าเกี่ยวกับโครงการ
├── Backtest.html               # หน้าแบบทดสอบประเมินผล Backtest
├── community.html              # หน้าชุมชนแลกเปลี่ยนความรู้
├── consult.html                # หน้าศูนย์ให้คำปรึกษา
├── cyberthreats.html           # หน้าบทเรียนภัยคุกคามทางไซเบอร์
├── DailyCY.html                # หน้าเกร็ดความรู้รายวัน
├── decodeimage.html            # หน้าเกมถอดรหัสภาพ
├── facetoface.html             # หน้าจำลองสถานการณ์การเผชิญหน้า
├── fakeapp.html                # หน้าจำลองการตรวจสอบแอปพลิเคชันปลอม
├── games.html                  # หน้าศูนย์รวมมินิเกม
├── GuidePR.html                # หน้าคู่มือการสื่อสารและประชาสัมพันธ์
├── index.html                  # หน้าหลักของเว็บไซต์
├── knowledgebase.html          # หน้าคลังความรู้
├── learning.html               # หน้าโมดูลการเรียนรู้
├── lessons.html                # หน้าบทเรียนหลัก
├── matchgame.html              # หน้าเกมจับคู่สัญลักษณ์และความรู้
├── parent.html                 # หน้าคู่มือสำหรับผู้ปกครอง
├── roleplay.html               # หน้าจำลองบทบาทสมมติ
├── skills.html                 # หน้าทักษะความปลอดภัยทางไซเบอร์
├── spottheflag.html            # หน้าเกม Spot the Flag
├── spottheflagresult.html      # หน้าแสดงผลลัพธ์เกม Spot the Flag
├── statistic.html              # หน้าแดชบอร์ดสรุปสถิติ
├── Testready.html              # หน้าทดสอบความพร้อมก่อน-หลังเรียน
└── translatecyber.html         # หน้าแปลความรู้และคำศัพท์ไซเบอร์

```
##  การรองรับการแสดงผล (Responsive Support)
โครงสร้างหน้าเว็บได้รับการออกแบบพร้อมปรับแต่งผ่าน `css/mobile-nav.css` เพื่อรองรับการแสดงผลทั้งบนหน้าจอ Desktop, Tablet และ Smartphone



