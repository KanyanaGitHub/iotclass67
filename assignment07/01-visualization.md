# Data Visualization.

ข้อมูลที่จะนำมาแสดงนั้นเป็นข้อมูลที่ได้จากเครื่อง Gateway โดยข้อมูลที่ดึงมาแสดงจะ
ประกอบด้วย 1. อุณหภูมิ 2. ความชื้น 3. แสง 4. แรงดันไฟฟ้า  5. สถานะ Gateway

- # IOT sensuor Humidity
![Example Image](Humi.png)

- # IOT sensor AVG Temperature
![Example Image](AVGTemp.png)

- # IOT sensuor Luminosity
![Example Image](Lumi.png)

- # IOT sensuor Pressure
![Example Image](Presure.png)

- # IOT sensor Temperature
![Example Image](Temp.png)

- # IOT 10 sensor map dashbord
![Example Image](10sensor.png)

- # Node Exporter
![Example Image](Node.png)

- # วิธีการทำ IOT 10 sensor map dashbord

1. ลง Plug in Flowcharting จาก (https://algenty.github.io/flowcharting-repository/INSTALL.html)

2. เลือกใช้ plug in ใน dashboard

![Example Image](Step2.png)

3. เลือกดึงข้อมูลจาก Prometheus โดยเซ็ตข้อมูลที่ต้องการใน Metric

![Example Image](Step3.png)

- เซ็ต Options เพื่อความสดวกในการเรียกใช้

![Example Image](Step3_1.png)

4. เลื่อนไปที่ Rule เพื่อ เซ็ต จุดวางเซ็นเซอร์แต่ละตัว

![Example Image](Step4_1.png)

- เซ็ตข้อมูลที่ต้องการดึง

![Example Image](Step4_2.png)

- เซ็ตสี่ที่ต้องการ

![Example Image](Step4_3.png)

- เลือก Opject และ Text ที่ต้องการแสดง

![Example Image](Step4_4.png)

- save, apply