# week4-grid-lab

## git command used in this lab
ตอนที่ 1: การสร้าง Complex Layout ด้วย CSS Grid  
- git config --global user.name "Supakan06"
- git config --global user.email "66160033@go.buu.ac.th"
- git clone https://github.com/Supakan06/week4-grid-lab
- สร้างไฟล์ index.html และ css/styles.css
- git add .
- git commit -m "init project"  
- git push

- git checkout -b development 
- git checkout -b feature/homepage
- git add index.html
- git commit -m "เพิ่มโครงสร้าง HTML พื้นฐาน"
- git add css/styles.css
- git commit -m "เพิ่ม Grid Layout พื้นฐาน"
- git add css/styles.css
- git commit -m "เพิ่ม Media Queries สำหรับ Responsive Design"  
- git add index.html
- git commit -m "เพิ่มเนื้อหาจําลองสำหรับทดสอบ Responsive"
- git add css/styles.css
- git commit -m "เพิ่ม CSS Animations" 
- git add css/styles.css
- git commit -m "เพิ่ม Hover Effects" 

ตอนที่ 2: การสร้าง Masonry Layout ด้วย CSS Grid 
- git checkout -b feature/gallery   
- สร้างไฟล์ gallery.html, css/styles-gallery.css และ js/script.js 
- git add .  
- git commit -m "init gallery"   
- git add gallery.html  
- git commit -m "สร้างโครงสร้าง HTML สำหรับแกลเลอรี่"
- git add css/styles-gallery.css
- git commit -m "เพิ่ม Masonry Layout ด้วย CSS Grid" 
- git add css/styles-gallery.css
- git commit -m "เพิ่ม Media Queries สำหรับ Responsive Gallery"
- git add gallery.html  
- git commit -m "เพิ่มรูปภาพและ Lazy Loading" 
- git add css/styles-gallery.css
- git commit -m "เพิ่ม Hover และ Loading Animations" 
- git add js/script.js
- git commit -m "เพิ่ม Filter Animations"
- git add gallery.html
- git commit -m "เชื่อมต่อ JavaScript"  

ตอนที่ 3: Push ขึ้น Github
- git checkout development 
- git add README.md 
- git commit -m "git command used in this lab" 
- git merge feature/homepage 
- git merge feature/gallery 
- git push origin development