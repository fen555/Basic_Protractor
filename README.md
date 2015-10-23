# Basic_Protractor

## เข้าไปที่ link 
```
http://www.protractortest.org/
```
#### ลง protractor
```
npm install -g protractor
```
#### ถ้าไม่ได้ให้เปลี่ยนเป็น ลง protrator
```
sudo npm install -g protractor
```
#### ต่อด้วย update
```
sudo npm install webdriver-manager update
```
#### ลอง start ดูนะ
```
webdriver-manager start
```
#### ถ้าไม่ได้ให้ลอง
```
sudo apt-get install openjdk-7-jre-headless
```
#### ลอง start อีกรอบดูนะ
```
webdriver-manager start
```
#### เปิดอีก tab (Ctrl+Shift+t) แล้ว run
```
protractor conf.js
```
## การอ่านไฟล์ spec
* describe = คำอธิบายก่อนจะ test
* browser.get('.....') = เปิด web browser แล้วจะเข้าไปใน link ใน .....
* element = การดึงค่า
* send = การส่งค่า
* expect = คาดหวัง เป็นคำสั่งที่ใช้ในการ test (ผลลัพธ์ที่ต้องการ)
