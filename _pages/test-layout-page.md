---
layout: default
title: "หน้าทดสอบ Layout ใหม่ (พร้อม Sidebar)"
description: "ทดสอบการทำงานของ default layout, CSS พื้นฐาน, และ Custom Sidebar Menu"
permalink: /test-layout/

# ส่วนสำคัญ: กำหนดให้แสดง sidebar และดึงเมนูเข้ามา
sidebar:
  - title: "เมนูนำทาง" # หัวข้อที่จะแสดงเหนือเมนูใน sidebar
    html: "{% include custom_sidebar_menu.html %}" # คำสั่งให้ดึงไฟล์เมนูที่คุณสร้างไว้มาแสดง
---

## สวัสดี! นี่คือหน้าทดสอบ Layout และ Sidebar

ถ้าทุกอย่างถูกต้อง หน้านี้ควรจะ:
* แสดงเนื้อหาหลักทางด้านหนึ่ง (น่าจะด้านซ้าย)
* และมี **Sidebar Menu** ที่มีหัวข้อ "เมนูนำทาง" (ที่คุณสร้างจาก `custom_sidebar_menu.html`) แสดงอยู่อีกด้านหนึ่ง (น่าจะด้านขวา)
* ลองตรวจสอบการทำงานของเมนูใน Sidebar ด้วยนะครับ (การคลิก, ลิงก์, สไตล์ CSS ที่คุณใส่ในไฟล์ include)
