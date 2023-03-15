# KensingtonAirline_LicensePlate

## WEEK 2
- Using Sarun's_ThangLuang.ttf font to generate character to predict license plate
- Use keras ImageDataGenerator to do data augmentation
- Train character prediction model using CNN 
- Use OpenCV to detect license plate and create bounding box for each character
- Use model to predict character in bounding box

## WEEK 3
- Fixes bounding box problem
- Add more data to dataset
- Delete unnessary data from dataset
- Changes data augmentation method
- Changes model structure

## How to run
- เปิดไฟล์ .ipynb ใน Google Colab
- ถ้าหากต้องการทดลองเทรนโมเดลแล้วนำไปใช้ ให้อัพโหลดไฟล์ dataset.zip ลง session storage แล้วรัน cell ที่ 1 เพื่อทำการ unzip ไฟล์
- จากนั้นรัน cell ที่ 3 เพื่อทำการเตรียมข้อมูล และ cell ที่ 4 เพื่อทำการเทรนโมเดล
- เมื่อเทรนเสร็จแล้วให้อัพโหลดรูปที่ต้องการทำการตรวจจับ license plate ลง session storage แล้วรัน cell ที่ 5 เพื่อทำการตรวจจับ license plate รูปที่เป็น default คือ image8.jpg แต่ถ้าหากต้องการเปลี่ยนให้อัพโหลดรูปที่ต้องการลง session storage แล้วเปลี่ยนชื่อไฟล์ของ original_image ใน cell 5 ให้ตรงกับชื่อไฟล์ที่อัพโหลด
- หากไม่ต้องการเทรนโมเดลเองเนื่องจากใช้เวลานานมากให้อัพโหลดไฟล์ OCR.h5 และรูปภาพลง session storage แล้วรัน cell ที่ 5 ได้เลย
- Cell ที่ 2 นั้นไม่จำเป็นจะต้องรันเนื่องจากเป็นโค้ดสำหรับ generate dataset ซึ่งเราได้ทำการ generate ไว้แล้วและอัพโหลดไฟล์ dataset.zip ไว้แล้ว ซึ่งมีการแก้ไขและเพื่มข้อมูลเข้าไปนอกเหนือจากที่ generate ออกมา