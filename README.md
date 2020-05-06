# Proxumer Backend Exam

สร้าง restful api สำหรับจัดการโปรโมชั่น

## File Stucture

- mock-database คือ directory ที่จำลอง ค่าที่ได้จาก database table promotion และ brand
- README.md รายละเอียดโจทย์

## ตัวอย่าง Endpoint API

```
[GET] /api/promotions //แสดงโปรโมชั่นทั้งหมด
[GET] /api/promotions?name={querystring} //ค้นหาโปรโมชั่นด้วยชื่อ
[POST] /api/promotions //เพิ่มโปรโมชั่น
...
// endpoint อื่นๆสามารถเพิ่มเพื่อให้ครอบคลุม data ทั้งหมดได้
```

ใน Project จะไม่สามารถรันได้ ผู้ทำข้อสอบ จำเป็นต้องลง package อื่นๆเพิ่มเติม เพื่อให้สามารถรันได้

```
** ใช้ syntax import ในการเรียกใช้ file
** ใช้ syntax export ในการทำให้ file อื่นเรียกใช้
```

## เกณฑ์การให้คะแนน (เต็ม 100 คะแนน)

- สามารถ run ได้อย่างถูกต้อง ไม่มี error (100 คะแนน)
- เปลี่ยนจาก restful เป็น graphql (จะได้รับคะแนนพิเศษ)
- ต่อเข้า database postgres, mysql (จะได้รับคะแนนพิเศษ)
- สามารถเขียน service อะไรก็ได้ ที่เกี่ยวข้องเพิ่มเติมนอกเหนือจากโจทย์ (จะได้รับคะแนนพิเศษ)
