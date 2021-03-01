# Assignment#1 การติดตั้ง Jenkins ใช้งานร่วมกับ GIT ,Python และ Robot Framework

<br>

## ขั้นตอนการติดตั้ง Jenkins

<br>
<img src="image_jenkins/01.PNG" width="500"/>
<br>

- ค้นหาว่า Jenkins


<br>

<br>
<img src="image_jenkins/02.PNG" width="800"/>
<br>

- กดDownload


<br>

<br>
<img src="image_jenkins/03.PNG" width="800"/>
<br>

- กด Windows

<br>

<br>
<img src="image_jenkins/04.PNG" width="200"/>
<br>

- รอการดาวน์โหลด

<br>

<br>
<img src="image_jenkins/05.PNG" width="500"/>
<br>

- กด Next

<br>

<img src="image_jenkins/06.PNG" width="500"/>
<br>

- กด Next

<br>

<img src="image_jenkins/07.PNG" width="500"/>
<br>

- เลือก Run as service as LocalSystem
- กด Next

<br>

<img src="image_jenkins/08.PNG" width="500"/>
<br>

- เลือก port
- กด Next

<br>

<img src="image_jenkins/09.PNG" width="500"/>
<br>

- กด Next

<br>

<img src="image_jenkins/10.PNG" width="500"/>
<br>

- กด Next

<br>

<img src="image_jenkins/11.PNG" width="500"/>
<br>

- กด Install

<br>

<img src="image_jenkins/12.PNG" width="500"/>
<br>

- รอ

<br>

<img src="image_jenkins/13.PNG" width="500"/>
<br>

- กด Finish

<br>



<img src="image_jenkins/14.PNG" width="800"/>
<br>

- เมื่อมีหน้าเว็บขึ้นมา ให้ทำการค้นหาไฟล์ Password ตามที่อยู่ตัวสีแดง
- แล้วทำการกรอก Password ลงไป

<br>

<img src="image_jenkins/15.PNG" width="800"/>
<br>

- กด Install suggested plugins

<br>

<img src="image_jenkins/16.PNG" width="800"/>
<br>

- แล้วรอการติดตั้งสักครู่

<br>

<img src="image_jenkins/17.PNG" width="800"/>
<br>

- สำหรับการเข้าครั้งแรก ให้กรอกแบบฟอร์มตามที่กำหนดให้ถูกต้อง

<br>

<img src="image_jenkins/18.PNG" width="800"/>
<br>

- เมื่อเสร็จแล้ว จะมีหน้าแสดง URL + port ขึ้นมา ให้ทำการบันทึกไว้
- กด Save and Finish

<br>

<img src="image_jenkins/19.PNG" width="800"/>
<br>

- กด Start using Jenkins

<br>


## การสร้างโปรเจคใน Jenkinds
<br>

<img src="image_jenkins/20.PNG" width="800"/>
<br>

- เมื่อเข้ามาแล้ว ให้กดที่ Create a Job เพื่อสร้างไฟล์โปรเจคใหม่ขึ้นมา

<br>

## การสร้างโปรเจคใน Jenkinds ร่วมกับการใช้ GIT 

<br>

<img src="image_jenkins/30.PNG" width="1000"/>
<br>

- ให้ตั้งชื่อโปรเจค โดยในที่นี้จะตั้งชื่อว่า Assignment1_jenkinds_GIT
- แล้วเลือก Freestyle Project
- แล้วกด Next

<br>

<br>

<img src="image_jenkins/31.PNG" width="1000"/>
<br>

- จะได้หน้าเพจแบบนี้ขึ้นมา
- ทำการ Configure เพื่อตั้งค่าโปรเจคของเรา

<br>

<br>

- เลือกไปที่ Repository URL ที่อยู่ใต้แท็บ Source Code Management
- ให้ใส่ที่อยู่ Repository ของเราที่สร้างไว้ ซึ่งมีที่อยู่ว่า https://github.com/friend-anupong/Assignment-1

- แล้วตรง Branch ให้ใส่ตามที่ตั้งไว้ ซึ่งมีชื่อว่า */main
- แล้วกด Save

<br>

<img src="image_jenkins/33.PNG" width="1000"/>
<br>

- Save แล้ว ให้กด Build Now 
- แล้วคลิกเข้าไปที่ตัวเลขที่แสดงไว้ข้างวางกลมสีน้ำเงิน

<br>

- แล้วกดเข้าไปที่ Console Output เพื่อดูผลการรัน

<br>

## การสร้างโปรเจคใน Jenkinds ร่วมกับการใช้ภาษา Python


<img src="image_jenkins/35.PNG" width="1000"/>
<br>

- ให้ตั้งชื่อโปรเจค โดยในที่นี้จะตั้งชื่อว่า Assignment1_jenkinds_Python
- แล้วเลือก Freestyle Project
- แล้วกด Next

<br>

<img src="image_jenkins/36.PNG" width="1000"/>
<br>

- แล้วกดออกมาที่หน้า Dashboard
- เข้าไปที่ Manage Jenkins 

<br>

<img src="image_jenkins/37.PNG" width="1000"/>
<br>

- เข้าไปที่ Manage Plugins เพื่อตั้งค่าหรือติดตั้ง Plugins ต่างๆเพิ่มเติม

<br>

<img src="image_jenkins/38.PNG" width="1000"/>
<br>

- ค้นหาคำว่า Python แล้วทำการติดตั้งทั้งหมด
- และ Restart Jenkins

<br>

<img src="image_jenkins/39.PNG" width="1000"/>
<br>

- เมื่อทำการติดตั้งเสร็จแล้ว ให้ทำการกดไปที่ config เพื่อตั้งค่าต่างๆ

<br>

<img src="image_jenkins/40.PNG" width="1000"/>
<br>

- ไปที่แท็บ Build แล้วเลือกตรงแถบข้างล่างว่า Execute Python Script
- ใส่ Code ภาษา python ลงไปเพื่อทำการทดสอบ

<br>

<img src="image_jenkins/41.PNG" width="1000"/>
<br>

- ทำการกด Build Now และคลิกเข้าไปที่ตัวเลขที่แสดงไว้ข้างวางกลมสีน้ำเงิน

<br>

- ทำการกด Console Output เพื่อดูผลลัพธ์

<br>


## การสร้างโปรเจคใน Jenkinds ร่วมกับการใช้ Robot Framework

<br>
<img src="image_jenkins/43.PNG" width="1000"/>
<br>

- ให้ตั้งชื่อโปรเจค โดยในที่นี้จะตั้งชื่อว่า Assignment1_Robotframework
- แล้วเลือก Freestyle Project
- แล้วกด Next

<br>

<img src="image_jenkins/44.PNG" width="1000"/>
<br>

- เข้าไปที่ configure
- เลือกแท็บ Build
- แล้วไปที่ Build กดตรงที่ Execute Windows batch command
- Set path ที่ติดตั้ง Robot Framework และ Seleniun Library ไว้ เพื่อให้รันโปรแกรมได้
- เขียนคำสั่งเรียกใช้ไฟล์ .Robot โดยเรียกไฟล์ที่สร้างไว้ตาม path ที่เก็บข้อมูลไว้

<br>

<img src="image_jenkins/script.PNG" width="400"/>
<br>

- ตัวอย่าง code ในไฟล์ robot

<br>

<img src="image_jenkins/45.PNG" width="1000"/>
<br>

- ตั้งค่า path นำเอาข้อมูลผลการรันมาสร้างกราฟ
- ตั้งค่า % ในการพล็อตกราฟ
- แล้วกด Save

<br>

<img src="image_jenkins/46.PNG" width="300"/>
<br>

- แล้วกด Build Now

<br>

<img src="image_jenkins/47.PNG" width="1000"/>
<br>

- จะได้ผลการรันของ Robotframework ดังภาพข้างต้น
- คลิกเข้าไปที่ตัวเลขที่แสดงไว้ข้างวางกลมสีน้ำเงิน 

<br>

<img src="image_jenkins/48.PNG" width="1000"/>
<br>

- จะได้ผลลัพธ์ ดังนี้

<br>

<img src="image_jenkins/50.PNG" width="1000"/>
<br>

- กดไปที่ Console Output เพื่อแสดงผลลัพธ์ที่ได้

<br>


<img src="image_jenkins/51.PNG" width="1000"/>
<br>

- ผลลัพธ์จากการทดสอบอื่นๆ ของ Robot Framework

<br>

<img src="image_jenkins/dashboard.PNG" width="1000"/>
<br>

- ผลลัพธ์รวมทั้งหมดจากหน้า Dashboard

<br>



