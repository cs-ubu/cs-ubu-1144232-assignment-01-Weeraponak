## HomeWork 1

ให้เขียนสรุปคำสั่ง CLI ด้วย Linux Terminal ที่เรียนมาทั้งหมด
## ตัวอย่าง

ลำดับ | ชื่อ-สกุล
-----|-------
1    |เด็กดี
2    |เรียบร้อย

:heart_eyes: :sleeping: :persevere:  :imp:  :sunglasses: 
:ok_hand: :+1:
## Upgrade Ubuntu
ขั้นตอน| คำสั่ง| คำอธิบาย
----- |---- |----------
1     | sudo apt update| Make sure you are up-to-date
2     | sudo apt upgrade| Make sure you are up-to-date
3     | sudo apt dist-upgrade| Handle software dependencies with new versions of packages
4     | sudo apt-get autoremove| Remove dependencies from uninstalled applications
5     | sudo apt install update-manager-core| Install the required package to upgrade between releases
6     | sudo do-release-upgrade| Run the ubuntu upgrade utility
7     | sudo reboot| Restart System

:musical_note: :thumbsup: :ok_hand:  :information_desk_person:  :cop:  :wave: :running: 

   คำสั่ง            |   คำอธิบาย
 ---------         | ---------
lsb_release -a     | ตรวจสอบเวอร์ชัน Linux Ubuntu
sudo apt install   | ติดตั้งโปรแกรมจาก package apt
tree	             | แสดงไฟล์และโฟลเดอร์ทั้งหมด
pwd	               | แสดงตำแหน่ง directory ปัจจุบัน
cd	               | เปลี่ยนตำแหน่ง directory
echo	             | แสดงตัวหนังสือที่พิมพ์
ls	               | แสดงไฟล์และโฟลเดอร์ทั้งหมด
tree -L 1          | แสดงไฟล์และโฟลเดอร์ที่ปรากฎเท่านั้น
tree -L 2	         | แสดงไฟล์และโฟลเดอร์ที่ปรากฎและภายในโฟลเดอร์อีกชั้นหนึ่ง
mkdir	             | สร้างโฟลเดอร์
touch	             | สร้างไฟล์เปล่า
rm	               | ลบไฟล์หรือโฟลเดอร์
mv	               | ย้ายไฟล์หรือโฟลเดอร์
rm -rf	           | ลบโฟลเดอร์
help	             | แสดงคำสั่งที่สามารทใช้ได้
df	               | แสดง process ที่กำลังทำงาน
df -h	             | แสดง process ที่กำลังทำงานในแบบที่อ่านง่าย
free	             | แสดงพื้นที่ว่างใน RAM
free -h	           | แสดงพื้นที่ว่างใน RAM ในแบบที่อ่านง่าย
uname	             | แสดงชื่อระบบปฎิบัติการ
uname -a	         | แสดงชื่อระบบปฎิบัติการแบบเต็ม
ps -ef             | แสดง process ที่กำลังทำงาน
kill -9	           | ปิดโปรแกรมตาม pid
killall	           | ปิดโปรแกรมตาม ชื่อโปรแกรม
top	               | แสดง process ที่กำลังทำงาน	
lsusb 	           | แสดง usb ที่กำลังเชื่อมต่ออยู่
lshw	             | แสดงข้อมูล hardware
find	             | ค้นหาไฟล์
whoami	           | แสดงชือ user
sudo adduser	     | สร้าง user ใหม่
su	               | เปลี่ยนไปใช้งานอีก user
passwd	           | เปลี่ยน password ของ user ปัจจุบัน
exit	             | ออกจาก user ปัจจุบัน
sudo addgroup	     | สร้าง group
sudo delgroup	     | ลบ group
