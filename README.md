# C# Coding Standards and Naming Conventions

## Directory Name
- ขึ้นต้นด้วยตัวอักษรพิมพ์ใหญ่ เช่น
```
Model
```

## File Name
- ใช้รูปแบบการตั้งชื่อเมธอดเป็นแบบ **Pascal Case (Upper Camel Case)** ขึ้นต้นด้วยตัวอักษรพิมพ์ใหญ่ เช่น
```
Order.cs
OrderController.cs
```

## Variable Name
- ชื่อตัวแปรเป็นคำเดียวให้ตั้งชื่อเป็นพิมพ์เล็กทั้งหมด เช่น
```
day, month, year
```

- ชื่อตัวแปรมีความยาวตั้งแต่ 2 คำขึ้นไป ให้คำหลังขึ้นตันด้วยตัวอักษรตัวใหญ่เสมอ ในรูปแบบ **camelCase** เช่น
```
startDay, endMonth
```

- ชื่อตัวแปรเก็บค่าให้เติม "List" ต่อท้ายตัวแปรเสมอ เช่น
```
orderList

```

- ชื่อตัวแปร Constant ให้ตังชื่อเป็นตัวอักษรพิมพ์ใหญ่ทั้งหมด เช่น
```
HOUR, MINUTE
```

## Method Name
- ใช้รูปแบบการตั้งชื่อเมธอดเป็นแบบ **Pascal Case (Upper Camel Case)** ขึ้นต้นด้วยตัวอักษรพิมพ์ใหญ่ เช่น
```
CalculateDate()
```

## Class Name
- ใช้รูปแบบการตั้งชื่อคลาสเป็นแบบ **Pascal Case (Upper Camel Case)** ขึ้นต้นด้วยตัวอักษรพิมพ์ใหญ่ เช่น
```
Employee.cs
TestEmployee.cs
```

## ข้อตกลง Commit Message ร่วมกัน
`[Created]: สร้างไฟล์ใหม่`

`[Edited]: แก้ไข code ในไฟล์เดิมที่มีอยู่แล้ว รวมถึงกรณี refactor code`

`[Added]: กรณีเพิ่ม function, function test ใหม่เข้ามา`

`[Deleted]: ลบไฟล์ออก`

* ให้เขียนรายละเอียดด้วยว่าแก้ไขอะไรและทำที่ตรงไหน





