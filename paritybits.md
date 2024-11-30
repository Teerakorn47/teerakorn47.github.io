**Keyword : “Parity bits”**

| **หัวข้อ**       | **แหล่งที่มา: CISSP Glossary - Student Guide**                                                                                                       | **แหล่งที่มา: NIST Glossary**                                                                                                                                   |
|-------------------|--------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------|
| **คำอธิบาย**     | RAID technique; logical mechanism used to mark striped data; allows recovery of missing drive(s) by pulling data from adjacent drives. | A checksum computed on a block of bits by summing the individual bits in the block, then discarding all but the low-order bit of the sum. See checksum.   |
| **คำแปล (ChatGPT)** | "กลไกทางตรรกะที่ใช้ในการทำเครื่องหมายข้อมูลแบบแบ่งแถบ (striped data); ช่วยให้สามารถกู้คืนไดรฟ์ที่สูญหายได้ โดยดึงข้อมูลจากไดรฟ์ที่อยู่ติดกัน"   | "Checksum ที่ถูกคำนวณบนบล็อกของบิต โดยการคำนวณผลรวมแบบไบนารีของบิตแต่ละตัวในบล็อก แล้วทิ้งบิตทั้งหมดที่อยู่นอกเหนือจากบิตลำดับต่ำสุดของผลรวมออกไป"    |
| **คำแปล (Gemini)** | "เทคนิค RAID; กลไกเชิงตรรกะที่ใช้ทำเครื่องหมายข้อมูลในรูปแบบแถบ; อนุญาตให้กู้คืนไดรฟ์ที่หายไป (ไดรฟ์) โดยดึงข้อมูลจากไดรฟ์ที่อยู่ติดกัน"          | "Checksum คือ ค่าตรวจสอบความถูกต้องของข้อมูล (data integrity) โดยคำนวณจากบล็อกของบิต (bits) ด้วยวิธีการบวกเลขฐานสอง (binary sum) ของแต่ละบิตในบล็อกนั้น จากนั้นนำผลรวมที่ได้มาตัดทอนเหลือเพียงบิตต่ำสุด (low-order bit) เท่านั้น" |

---

**สรุปโดยตัวเอง (Myself):**  
กลไกที่ใช้ตรวจสอบหรือแก้ไขข้อผิดพลาดในข้อมูล  

**ตัวอย่างในชีวิตประจำวัน:**  
การส่งข้อความผ่านอินเทอร์เน็ต: เมื่อเราส่งอีเมลหรือข้อความผ่านเครือข่าย ระบบจะใช้ parity bits เพื่อตรวจสอบว่าข้อมูลถึงปลายทางโดยไม่มีข้อผิดพลาด เช่น หากมีบิตบางตัวเสียหายระหว่างการส่ง ระบบจะตรวจจับและพยายามแก้ไข