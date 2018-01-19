# Basic
### By MAN SD

```
git init
เป็นคำสั่งที่เอาไว้เพื่อสร้าง git repository เปล่าๆขึ้นมา โดย Git จะทำการสร้างโฟลเดอร์  .git ขึ้นมาภายในโปรเจ็คของเรา (Hidden ไว้อยู่) 
```
```
git add README
เป็นคำสั่งอธิบายวิธีที่เราจะทำให้ไฟล์เราโดน track โดย Git ก็คือการใช้ git add README
```
```
git commit -m "add sample index page"
เราจะทำการ commit ด้วยคำสั่ง git commit -m "YOUR MESSAGE" ฉะนั้น commit แรกผมจะใส่ข้อความบอกไว้ว่า ได้ทำการเพิ่มไฟล์ index แล้วนะ
```
```
git remote add origin git@github.com:SulaimanDaeboh/readone.git
เป็นคำสั่งที่เพิ่ม url ของ remote (Server) เพื่อให้รู้ว่าเราจะฝากโค๊ดไว้ที่ใด
กลับมาที่เครื่องเรา
```
```
git push -u origin master
-u : เอาไว้จำ parameter origin master ต่อไปก็แค่พิมพ์ git push
origin : คือชื่อ alias ของ remote (github)
master : คือชื่อ branch ที่เราต้องการ push ขึ้นไป
```
```
git clone https://github.com/SulaimanDaeboh/readone
เป็นคำสั่ง clone โฟลเดอร์จาก git ลงเครื่องที่ใช้งาน
```
```
git > abc.txt
เป็นคำสั่ง copy คำสั่งของ git ทั้งหมดลงในไฟล์ abc.txt
```
```
git status
เพื่อตรวจสอบสถานะ repository ของเรา
```
#### 19/01/2018
```
git checkout ชื่อไฟล์.???
คำสั่งการย้อนกลับ (discard edit)
```
```
git reset HEAD ชื่อไฟล์.???
คำสั่งย้อนกลับ หลังจากเรา save ไปแล้วหลังจากก็พิมพ์คำสั่งนี้ด้วย git checkout --ชื่อไฟล์.??? (discard add)
```
```
git reset --soft "HEAD^"
คำสั่งย้อนกลับ (discard commit)
```