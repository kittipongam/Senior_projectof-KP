
# Demonstration System of mass-customized production and  OEE monitoring for Industry 4.0 Solution

## INTRODUCTION


>

    In order to provide an industry 4.0 solution for improving a production line to be more effective, this thesis presents a demonstration system of mass-customized production and overall equipment effectiveness (OEE) monitoring. A color-based sorting and packing system is implemented for use as an illustrative case study to emulate the flexible manufacturing system that creates custom-made options. The packing conveyor is controlled by SIEMENS S7-1200 programmable logic controller (PLC) that executes its instructions by using TIA PORTAL software. To sort products in according to their respective colors, the DRS-40-L3 SCARA robot is controlled by DELTA ASDA-MS robot controller that provides accessing its data through DROE software.
    Moreover, the safety light curtain is installed to protect personnel from injuries related to hazardous robot motion. The WooCommerce integrated with WordPress enterprise resource planning (ERP) website is used for getting data of customers, products, and orders. The Archestra IDE-based databaseis created for transferring the order data from the ERP website to the implemented sorting and packaging system via Modbus TCP
    protocol as well as for calculating the OEE from three factors:availability, performance, and quality. The proposed demonstration system consists of three types of monitors, which are a touch screen to display operating statuses of the packing conveyor, a web- based screen to display customer order data, and a flat screen TV to display the calculated OEE. Based on the specifications of the robot and equipment used,
    simulation results for verifying the proposed OEE monitoring function are additionally
    included.

     ระบบสาธิตการผลิตตามความต้องการที่แตกต่างและการแสดงค่าโออีอีเพื่อเป็นทางเลือกในยุคอุตสาหกรรม 4.0 สําหรับการปรับปรุงสายการผลิตให้มีประสิทธิภาพมากยิ่งขึ้น โดยดําเนินการสร้างระบบคัดแยกสีและบรรจุภัณฑ์เพื่อใช้เป็นกรณีศึกษาในการเลียนแบบระบบการผลิตที่มีความยืดหยุ่นในการตอบสนองต่อความต้องการผู้บริโภค ส่วนสายพานลําเลียงของระบบ
    บรรจุภัณฑ์ถูกควบคุมด้วยพีแอลซีรุ่น SIEMENS S7-1200 ซึ่งมีการประมวลผลชุดคําสั่งโดยใช้ซอฟต์แวร์ TIA PORTAL ส่วนหุ่นยนต์สการารุ่น DRS-40-L3 ที่ใช้สําหรับการคัดแยกสินค้าด้วยสี ถูก
    ควบคุมด้วยตัวควบคุมหุ่นยนต์รุ่น DELTA ASDA-MS โดยตัวควบคุมหุ่นยนต์นี้มีการใช้ซอฟต์แวร์ DROE สําหรับการเข้าถึงข้อมูลของหุ่นยนต์ ยิ่งไปกว่านั้น ยังได้มีการติดตั้งม่านแสงนิรภัยเพื่อป้องกัน
    อันตรายที่จะเกิดขึ้นจากการเคลื่อนที่ของหุ่นยนต์ การรับรายการสั่งซื้อ ประเภทสินค้า และข้อมูลลูกค้า สามารถทําได้ด้วย WooCommerce ผ่านเว็บอีอาร์พีของ WordPress ส่วนฐานข้อมูลที่ถูก
    สร้างด้วย Archestra IDE ใช้สําหรับการถ่ายโอนข้อมูลสั่งซื้อจากเว็บอีอาร์พีไปยังระบบระบบคัดแยกและบรรจุภัณฑ์ที่สร้างขึ้นผ่านโปรโตคอล Modbus TCP และใช้สําหรับการคํานวณค่าโออีอีจากตัว
    แปร 3 ค่า คือ อัตราเดินเครื่อง ประสิทธิภาพเดินเครื่อง และอัตราคุณภาพ ระบบสาธิตการผลิตที่นําเสนอมีส่วนแสดงผล 3 แบบด้วยกัน ซึ่งประกอบด้วย จอแบบสัมผัสที่ใช้ในการแสดงสถานะการ
    ทํางานของส่วนสายพานลําเลียง ส่วนแสดงผลบนเว็บที่ใช้ในการแสดงข้อมูลการสั่งซื้อของลูกค้า และจอโทรทัศน์ที่ใช้ในการแสดงค่าโออีอีที่คํานวณได้ นอกจากนั้น ผลการเลียนแบบสําหรับการยืนยัน
    ความถูกต้องของฟังก์ชันการแสดงค่าโออีอียังได้นําเสนอในปริญญานิพนธ์นี้ อีกด้วย

>



## CONTENT
Industry 4.0

![image](https://user-images.githubusercontent.com/104770048/169227037-67bf9a84-9a9f-4c9a-8551-763626380dcc.png)

Ecommerce

![image](https://user-images.githubusercontent.com/104770048/169227164-04e083b1-395d-470d-981c-ba8cb064c993.png)

Ecommerce - Industry 4.0

![image](https://user-images.githubusercontent.com/104770048/169227252-9168e74f-5a51-42cb-86b3-e7616416386a.png)



Sorting and Packing System

![image](https://user-images.githubusercontent.com/104770048/169226854-65604af0-c8e1-4330-b408-c28cdd793bed.png)


OEE

![image](https://user-images.githubusercontent.com/104770048/169226742-82163404-b08d-42f8-bdd5-81ef4c2712dd.png)

Website

<p align="center">  
    <img width="75%" src="https://user-images.githubusercontent.com/104770048/169226924-3b11ba2b-b412-41a6-b8c4-845244649e97.png"> <br>
    <img width="75%" src="https://user-images.githubusercontent.com/104770048/169227989-5b849726-1492-4da4-bdc5-ebdf3c851fb3.png"> <br>
    <img width="75%" src="https://user-images.githubusercontent.com/104770048/169228023-5c3c829c-9e9f-4392-80db-1bfbd4333c13.png"> <br>
    <img width="75%" src="https://user-images.githubusercontent.com/104770048/169228063-55dfbf6e-d389-4789-bd37-d8bcbca032c6.png"> <br>
    <img width="75%" src="https://user-images.githubusercontent.com/104770048/169228108-89dd17df-d033-4b9d-b84b-87bea1722c96.png"> <br>
    <img width="75%" src="https://user-images.githubusercontent.com/104770048/169228156-3eac3a0e-0491-4c8e-8940-322c3009b4e1.png"> <br>
    
    <img width="33%" src="https://i.stack.imgur.com/RJj4x.png"> <br>
     ![image](https://user-images.githubusercontent.com/104770048/169226924-3b11ba2b-b412-41a6-b8c4-845244649e97.png)
     ![image](https://user-images.githubusercontent.com/104770048/169227989-5b849726-1492-4da4-bdc5-ebdf3c851fb3.png)
     ![image](https://user-images.githubusercontent.com/104770048/169228023-5c3c829c-9e9f-4392-80db-1bfbd4333c13.png)
     ![image](https://user-images.githubusercontent.com/104770048/169228063-55dfbf6e-d389-4789-bd37-d8bcbca032c6.png)
     ![image](https://user-images.githubusercontent.com/104770048/169228108-89dd17df-d033-4b9d-b84b-87bea1722c96.png)
     ![image](https://user-images.githubusercontent.com/104770048/169228156-3eac3a0e-0491-4c8e-8940-322c3009b4e1.png)   
</p>    

## CONCLUSION

>

    จากการดําเนินงานสร้างระบบสายพานลําเลียงและบรรจุ เพื่อเป็นกรณีศึกษาของระบบสาธิต การผลิตตามความต้องการที่แตกต่าง ประกอบด้วย เว็บเบราว์เซอร์ เพื่อเป็นช่องทางการเข้าถึงข้อมูล
    ต่าง ๆ ได้แก่ รูปแบบการจัดวางของสินค้าและบรรจุภัณฑ์ตามใบสั่งซื้อ และติดตามสถานะของสินค้า แก่ผู้ผลิตและผู้บริโภค ระบบสายพานลําเลียงและบรรจุ เพื่อสาธิตกระบวนการการลําเลียงและบรรจุ
    ผลิตภัณฑ์ ระบบป้องกันนิรภัย เพื่อสร้างความปลอดภัยให้กับผู้ปฏิบัติงาน และส่วนหน้าจอแสดงผล กราฟิก 3 ส่วน คือ การแสดงผลระบบควบคุมพื้นฐาน การแสดงผลระบบสกาดา และการแสดงค่าโออี
    อีของชุดสาธิต ผ่านหน้าจอโทรทัศน์ ซึ่งระบบได้ผ่านการทดสอบระบบ และจะถูกพัฒนาต่อไปเป็น ระบบสาธิตการผลิตตามความต้องการที่แตกต่างแบบเต็มรูปแบบ

>
