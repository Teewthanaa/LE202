บวกเลข x0 กับ 32 (เลขฐาน 16) แล้วไปเก็บไว้ที่ x1 ดังรูป

![image](https://user-images.githubusercontent.com/98943423/160593101-ebded76a-23c0-4790-bbd7-4119d084d05e.png)
นำ c0000000 ไปใส่ใน x2 แต่ใส่แค่บิทแรก ดังรูป

![image](https://user-images.githubusercontent.com/98943423/160593203-6fa185fe-996e-48ad-ac6c-9705e6c87a18.png)
นำค่า x1 มาแค่บิทเดียว ดูที่ address 00000020 ซึ่งคือตัวเลข 54 ไปเก็บใน x3 ดังรูป

![image](https://user-images.githubusercontent.com/98943423/160593271-90ffa6ab-4d21-421b-901d-2f0afee41ae1.png)
ตรวจสอบว่า x3 เท่ากับ x1ไหม ดังรูป

![image](https://user-images.githubusercontent.com/98943423/160593307-f1a56ade-7502-4e7c-858d-2668aa8ff7b5.png)
นำค่า x3 ไปใส่ใน x2 เพื่อแสดงตัวอักษร T ดังรูป

![image](https://user-images.githubusercontent.com/98943423/160593370-481016da-89ae-4fff-b152-59e21966f24e.png)
จากนั้นทำการเอา 1 ไปบวกกับ x1 แล้วไปเก็บใหม่ใน x1 ดังรูป

![image](https://user-images.githubusercontent.com/98943423/160593495-022495a3-f91f-44bd-b538-af75d1cb8b3b.png)
ทำการวนลูปโดย โดดย้อนไป -16 address 00000008 ดังรูป

![image](https://user-images.githubusercontent.com/98943423/160593575-35d0b0ed-421d-4f59-9494-d329f32ba5fc.png)
นำค่า x1 มาแค่บิทเดียว ดูที่ address 00000021 ซึ่งคือตัวเลข 4e ไปเก็บใน x3 ดังรูป

![image](https://user-images.githubusercontent.com/98943423/160593627-ed78ba42-1f59-4330-bc78-e2094d5990d2.png)
ตรวจสอบว่า x3 เท่ากับ x1ไหม ดังรูป

![image](https://user-images.githubusercontent.com/98943423/160593670-9ebe8e86-308e-4100-b963-4eb3596bbac3.png)
นำค่า x3 ไปใส่ใน x2 เพื่อแสดงตัวอักษร N ดังรูป

![image](https://user-images.githubusercontent.com/98943423/160593719-08626c17-31c1-4df5-a05e-a2384ad9ef12.png)
จากนั้นทำการเอา 1 ไปบวกกับ x1 แล้วไปเก็บใหม่ใน x1 อีกครั้ง ดังรูป

![image](https://user-images.githubusercontent.com/98943423/160593769-2ee30462-1df3-40f3-acd4-f0f2d258ca36.png)
ทำการวนลูปโดย โดดย้อนไป -16 address 00000008 ดังรูป

![image](https://user-images.githubusercontent.com/98943423/160593816-bb6c37ba-ddc2-4938-bcbf-a72574b22d04.png)
นำค่า x1 มาแค่บิทเดียว ดูที่ address 00000022 ซึ่งคือตัวเลข 00 ไปเก็บใน x3 ดังรูป

![image](https://user-images.githubusercontent.com/98943423/160593857-0ecf76c6-0c21-4644-9f6c-d561a744f277.png)
ตรวจสอบว่า x3 เท่ากับ x1ไหม ถ้าเท่ากันเมื่อไหร่แสดงว่าเงื่อนไขเป็นจริงและออกจากการวนลูป ดังรูป

![image](https://user-images.githubusercontent.com/98943423/160593895-e7397328-7946-423a-9494-ea57e0589910.png)
