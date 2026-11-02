# week4 # โครงสร้าง MTML และพื้นฐาน
#ผู้จัดทำ 
[นายวรวุฒน์ กาใจตรงง] รายวิชา: COM1303 การพัฒนาเว็บพื้นฐาน

1 การสร้างบัญชี GitHub ไปที่ GitHub และสร้างบัญชีผู้ใช้

2. สร้าง Repository (ที่เก็บงาน)
Repository ก็คือ "โฟลเดอร์โปรเจกต์" บน GitHub กดปุ่ม New ตั้งชื่อ แล้วเลือกว่าจะให้ใครเห็นได้บ้าง
Public: ใครก็เห็นได้
Private: เห็นเฉพาะเรา
การเชื่อมต่อกับ GitHub จากเครื่องคอมพิวเตอร์ ติดตั้ง Git บนเครื่องคอมพิวเตอร์ของคุณ จากนั้นเปิด terminal หรือ command prompt และตั้งค่า Git ด้วยคำสั่งต่อไปนี้:
[git config --global user.name "ชื่อของคุณ"]
[git config --global user.email "อีเมลของคุณ"" ]

4. การโคลน (Clone) Repository เพื่อโคลน repository จาก GitHub มายังเครื่องคอมพิวเตอร์ของคุณ:[
bash git clone https://github.com/username/repository.git]
หรือสรุปง่ายๆคือการโหลดไฟล์git ใหม่ในคอม

5. การเพิ่มและคอมมิตไฟล์ เพิ่มไฟล์ใหม่หรือแก้ไขไฟล์ใน repository
เพิ่มไฟล์ที่เปลี่ยนแปลงไปยัง staging area
[bash git add . คอมมิตการเปลี่ยนแปลง:]
[bash git commit -m "Initial commit" ดันการเปลี่ยนแปลงไปยัง GitHub:]
[bash git push origin main]

6. การสร้างและใช้งาน Branch สร้าง branch ใหม่:
git checkout -b ชื่อ-branch
git push origin ชื่อ-branch
(คำสั่งแรกสร้างสายใหม่และย้ายไปทำงานในสายนั้นเลย คำสั่งที่สองส่งขึ้น GitHub)

7. [Pull Request: ขอรวมงานกลับเข้าสายหลัก
เมื่อแก้งานใน branch เสร็จแล้ว ก็ไปที่ GitHub แล้วทำตามนี้
เปิดแท็บ Pull requests
กด New pull request
เลือก branch ที่ต้องการรวม
กด Create pull request และกรอกรายละเอียด]
[link]( https://www.youtube.com/watch?v=1ikeJmZNTDc&list=RD1ikeJmZNTDc&start_radio=1)
