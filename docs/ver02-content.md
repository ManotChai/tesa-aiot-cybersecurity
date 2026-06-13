# ver02 — NT × TESA Edition · สรุปเนื้อหาฉบับละเอียด

> **AIoT Cybersecurity Guideline Readiness Workshop** — เวอร์ชันโปรโมตคอร์สสำหรับ **National Telecom (NT)** ร่วมกับ **TESA**
> อ้างอิงเนื้อหาจากเอกสาร *AIoT_Cybersecurity_NT_Poster_FullSpec_v4*

## เส้นทาง (Routes)
| URL | คำอธิบาย |
|-----|----------|
| `/ver02` | หน้าเว็บ NT × TESA edition (responsive, scroll) |
| `/ver02/slides` | สไลด์เด็ค 6 หน้า (1536×1024) ผ่าน `<Deck>` |
| `/ver01` , `/responsive` | เวอร์ชันมาตรฐานเดิม (Standard Edition) |
| `/` | สไลด์เด็คต้นฉบับ |

ไฟล์หลัก: `components/views/Version2.tsx` (เว็บ) · `components/slides/Ver02Slides.tsx` (สไลด์) · `app/ver02/ver02.css` · `app/ver02/slides/v2s.css`

---

## 0. Brand / Header
- **แบรนด์:** โลโก้ NT (`nt-logo.svg` — แท่ง equalizer ทอง + "nt") × โลโก้ TESA + คำว่า **AIoT** (เขียว)
- **เมนู:** Why NT · Agenda · Roles · Sponsorship · Register
- **ปุ่มมุมขวา:** Standard Edition → (`/ver01`) · ▦ Slides (`/ver02/slides`)
- บนมือถือ: เมนูเป็น pill แถวที่ 2 แบบถาวร (ไม่มี hamburger)

---

## 1. Hero (id `#top`)
- **Eyebrow:** NT × TESA · OFFICIAL COLLABORATION
- **Badge:** 2-DAY INTENSIVE PROGRAM
- **หัวเรื่อง (H1):** **TESA AIoT CYBERSECURITY GUIDELINE READINESS WORKSHOP**
  (TESA = แดง, AIoT = ฟ้า, GUIDELINE = เขียว)
- **Sub:** Understanding Future AIoT Cybersecurity Requirements for Network Operators
- **คำโปรย:** เตรียมความพร้อมบุคลากร NT ให้เข้าใจแนวทาง AIoT Cybersecurity Guideline ของ สกมช. (NCSA) และสามารถประยุกต์ใช้กับโครงสร้างพื้นฐานและบริการขององค์กรได้อย่างมีประสิทธิภาพ
- **CTA:** REGISTER NOW · ★ สนับสนุนเต็มจำนวนโดย TESA
- **Pills:** FREE FOR NT · WORKSHOP + HANDS-ON LAB · THAI LANGUAGE

### Pillar 4 ใบ (การบรรจบของเทคโนโลยีที่คอร์สนี้ตอบโจทย์)
| # | หัวข้อ | คำอธิบาย |
|---|--------|----------|
| 1 | TELECOM INFRASTRUCTURE | โครงสร้างพื้นฐานโทรคมนาคมของ NT |
| 2 | AIoT CONVERGENCE | อุปกรณ์ AIoT เชื่อมต่อจำนวนมหาศาล |
| 3 | CYBER RESILIENCE | ลดความเสี่ยงและภัยคุกคามไซเบอร์ |
| 4 | NCSA READINESS | พร้อมรับแนวทาง สกมช. ในอนาคต |

---

## 2. Why NT Should Attend (id `#why`)
*ทำไมบุคลากร NT จึงควรเตรียมความพร้อมตั้งแต่วันนี้* — แสดงเป็น Convergence Hub infographic + กล่องเหตุผล 4 ข้อ

| # | เหตุผล (TH) | EN |
|---|-------------|-----|
| 01 | Network Operator ที่ต้องรองรับการมาของ AIoT จำนวนมหาศาล | NT infrastructure increasingly connects AIoT devices. |
| 02 | ข้อกำหนดด้าน Cybersecurity ของ สกมช. ที่ต้องคำนึงในการดำเนินการในอนาคต | Future governance requirements should be understood early. |
| 03 | เตรียมพร้อมต่อความเสี่ยงจากภัยคุกคามไซเบอร์ ให้ความปลอดภัยต่อบริการและข้อมูลสำคัญขององค์กร | Cybersecurity readiness reduces operational risk. |
| 04 | เสริมสร้างศักยภาพบุคลากร ให้พร้อมรับมือเทคโนโลยีและภัยคุกคามรูปแบบใหม่ | People readiness is a strategic investment. |

---

## 3. 2-Day Program Agenda (id `#agenda`)
*จากความเข้าใจภัยคุกคาม สู่มาตรการควบคุมเชิงปฏิบัติ*

### DAY 1 — UNDERSTANDING AIoT CYBERSECURITY
| # | โมดูล | สิ่งที่ได้เรียนรู้ |
|---|-------|------------------|
| 01 | AIoT Threat Landscape for Network Operators | เข้าใจภัยคุกคามที่เกิดขึ้นจริงในปัจจุบัน |
| 02 | NCSA Direction & AIoT Cybersecurity Guideline | เข้าใจทิศทางระดับชาติของ สกมช. ในอนาคต |
| 03 | Critical Information Infrastructure Protection | เข้าใจการปกป้องโครงสร้างพื้นฐานสำคัญ |
| 04 | AIoT Risk Assessment & Management | เข้าใจวิธีประเมินและบริหารความเสี่ยง |
| 05 | Cyber Drill Case Studies, Policy & Compliance | เข้าใจความรับผิดชอบด้านการกำกับดูแล |

**FOCUS:** เข้าใจภัยคุกคาม ทิศทาง สกมช. และการประเมินความเสี่ยงของโครงสร้างพื้นฐาน

### DAY 2 — PRACTICAL SECURITY CONTROLS
| # | โมดูล | สิ่งที่ได้เรียนรู้ |
|---|-------|------------------|
| 01 | Asset Visibility & Inventory for AIoT | รู้ว่ามีสินทรัพย์อะไรในระบบบ้าง |
| 02 | Device Identity & PKI Fundamentals | เข้าใจการสร้างความน่าเชื่อถือของอุปกรณ์ |
| 03 | Secure Connectivity & Network Segmentation | ลดพื้นที่การโจมตีด้วยการแบ่งเครือข่าย |
| 04 | Threat Detection, Monitoring & Incident Response | ตรวจจับและตอบสนองต่อภัยคุกคาม |
| 05 | Case Studies & Best Practices | เรียนรู้จากกรณีศึกษาและตัวอย่างจริง |

**FOCUS:** ลงมือกับมาตรการควบคุมจริง ตั้งแต่การมองเห็นสินทรัพย์ถึงการตอบสนองเหตุ

**ข้อมูลคอร์ส:** 09:00 – 16:30 ทั้ง 2 วัน · Workshop + Hands-on Lab · บรรยายภาษาไทย

---

## 4. Designed for Every Role (id `#roles`)
*เนื้อหาเดียวที่ตอบโจทย์ทั้งผู้บริหาร ผู้จัดการ และวิศวกรพร้อมกัน*

### A. EXECUTIVES & LEADERS — ผู้บริหารและผู้นำ
- **กลุ่ม:** VP · SVP · Director · Department Head
- เข้าใจผลกระทบเชิงธุรกิจ
- เข้าใจความรับผิดชอบด้านการกำกับดูแล
- เตรียมทิศทางเชิงกลยุทธ์
- **สิ่งที่จะได้รับ:** เข้าใจทิศทาง Cybersecurity ในอนาคตและผลกระทบต่อองค์กร

### B. MANAGERS & TEAM LEADERS — ผู้จัดการและหัวหน้าทีม
- **กลุ่ม:** Team Leader · Project Manager · Operations Manager
- แปลงนโยบายสู่การปฏิบัติ
- บริหารโครงการด้านความมั่นคงปลอดภัย
- ประเมินความเสี่ยงเชิงปฏิบัติการ
- **สิ่งที่จะได้รับ:** แปลงนโยบายเป็นแผนการดำเนินงานที่ทำได้จริง

### C. ENGINEERS & OPERATIONS — วิศวกรและทีมปฏิบัติการ
- **กลุ่ม:** Network · Infrastructure · Operations · Security Engineers
- เข้าใจมาตรการควบคุมเชิงเทคนิค
- นำแนวคิดไปประยุกต์ใช้จริง
- เพิ่มความมั่นใจในการทำงาน
- **สิ่งที่จะได้รับ:** เข้าใจมาตรการความมั่นคงปลอดภัย AIoT เชิงปฏิบัติ

---

## 5. What You Will Get & Key Outcomes (id `#outcomes`)

### What You Will Get (สิ่งที่จะได้รับ)
| หัวข้อ | รายละเอียด |
|--------|-----------|
| NCSA-ALIGNED KNOWLEDGE | องค์ความรู้ที่สอดคล้องกับทิศทางของ สกมช. |
| PRACTICAL GUIDANCE FOR NT | แนวทางปฏิบัติที่นำไปใช้กับ NT ได้จริง |
| AIoT RISK MITIGATION | แนวคิดลดความเสี่ยง AIoT ที่ลงมือทำได้ |
| TESA CERTIFICATE | ใบรับรองการเข้าร่วมจาก TESA |

### Key Outcomes (ผลลัพธ์ที่ได้)
1. เข้าใจแนวคิด AIoT Cybersecurity
2. ประเมินความเสี่ยงและกำหนดมาตรการควบคุม
3. เข้าใจเทคโนโลยีด้านความมั่นคงปลอดภัย
4. เตรียมพร้อมรับมาตรฐานในอนาคต
5. เพิ่มความมั่นใจและความพร้อม

---

## 6. Register + Sponsorship (id `#register`)
*สมัครเข้าร่วมอบรม — เตรียมความพร้อมทีม NT รับมือแนวทาง AIoT Cybersecurity ของ สกมช.*
(Sponsorship รวมเข้ากับ Register แล้ว — การ์ดฟรีซ้าย / รายละเอียด + QR ขวา)

### กล่อง "พิเศษ!" — ฟรีสำหรับ NT
- **ผู้อบรม NT ไม่มีค่าใช้จ่ายใด ๆ**
- มูลค่ารวม ~~20,000~~ บาท/ท่าน → **ฟรี! สำหรับบุคลากร NT**
- **ครอบคลุม:**
  - ค่าวิทยากรผู้เชี่ยวชาญ
  - ค่าดำเนินการจัดอบรมทั้งหมด
  - Coffee Break ตลอดงาน
  - อาหารว่างและเครื่องดื่มทั้ง 2 วัน

### รายละเอียดคอร์ส
| หัวข้อ | ค่า |
|--------|-----|
| DURATION | 2 วัน |
| TIME | 09:00 – 16:30 |
| FORMAT | Workshop + Hands-on Lab |
| LANGUAGE | ภาษาไทย |
| TARGET GROUP | ผู้บริหาร · ผู้จัดการ · วิศวกร · ทีมปฏิบัติการ NT |

- **ลงทะเบียน:** QR code + ปุ่ม REGISTER NOW! (สแกนเพื่อสมัครเข้าร่วมอบรม)

---

## 7. Footer / ติดต่อ
- แบรนด์: NT × TESA · AIoT
- ☎ 085-495-4294 · ✉ contact@tesa.or.th · 🌐 www.tesa.or.th
- © TESA — Thai Embedded Systems Association

---

## หมายเหตุด้านดีไซน์ (Design notes)
- **Why hub:** infographic เต็มกรอบ navy + กล่องเหตุผล 4 ใบล้อมรอบตำแหน่ง node (เท่ากันทุกใบ)
- **พื้นหลัง hero:** ภาพจริง `p1-bg.jpg` (เสาส่ง/กังหันลม/โครงข่าย + แสงเช้า)
- **Agenda & Roles:** ใช้ CSS **subgrid** จัดแถวให้ตรงกันข้ามคอลัมน์
- **Role/Tile icons:** line-art เฉพาะตัวแต่ละหัวข้อ (navy + เขียว); ไอคอน role เกยขอบบนกล่อง
- **Responsive:** เมนูแถว 2 ถาวร · tiles 2 กล่อง/แถว · smooth scroll
- **สไลด์เด็ค 6 หน้า:** 01 Title · 02 Why NT · 03 Day 1 · 04 Day 2 · 05 Roles · 06 Register/Sponsorship
