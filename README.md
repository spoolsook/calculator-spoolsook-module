
# คู่มือการใช้งาน Calulator-spoolsook

สร้างไว้ใช้บวกลบคูณหารตัวเลข 2 ตัวแบบชิลล์ๆ

สร้างตอนเรียน Node.js กับอาจารย์พล(Nextflow)

- สามารถบวกเลข 2 ตัวได้
- สามารถลบเลข 2 ตัวได้
- สามารถคูณเลข 2 ตัวได้
- สามารถหารเลข 2 ตัวได้ (ทำแล้วแต่ยังไม่สมบูรณ์)

## วิธีใช้งาน

  ต้องลง NodeJS ก่อนนะ [ดาวน์โหลดได้ที่นี่](https://nodejs.org/en/) 

  วิธี require module

```js
    const cal = require('./index');
```

### วิธีการบวก

สำหรับการบวกให้ใช้ function `plus()`

```js
    console.log(cal.plus(3, 6)); // 9
```

#### Refer npm
![1](https://user-images.githubusercontent.com/29914623/61846470-6f498d80-aed1-11e9-8a4a-cfd5a586a15a.png)