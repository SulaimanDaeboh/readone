<h1>Basic</h1>
```
$ git init เป็นคำสั่งที่เอาไว้เพื่อสร้าง git repository เปล่าๆขึ้นมา โดย Git จะทำการสร้างโฟลเดอร์  .git ขึ้นมาภายในโปรเจ็คของเรา (Hidden ไว้อยู่) 
```
$ git add README
เป็นคำสั่งอธิบายวิธีที่เราจะทำให้ไฟล์เราโดน track โดย Git ก็คือการใช้ git add README
git commit -m "add sample index page"
เราจะทำการ commit ด้วยคำสั่ง git commit -m "YOUR MESSAGE" ฉะนั้น commit แรกผมจะใส่ข้อความบอกไว้ว่า ได้ทำการเพิ่มไฟล์ index แล้วนะ
git remote add origin git@github.com:SulaimanDaeboh/readone.git
เป็นคำสั่งที่เพิ่ม url ของ remote (Server) เพื่อให้รู้ว่าเราจะฝากโค๊ดไว้ที่ใด
กลับมาที่เครื่องเรา
git push -u origin master
-u : เอาไว้จำ parameter origin master ต่อไปก็แค่พิมพ์ git push
origin : คือชื่อ alias ของ remote (github)
master : คือชื่อ branch ที่เราต้องการ push ขึ้นไป