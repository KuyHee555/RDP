1. สมัครการใช้งานNGROK เพื่อนำYour Auth Token มาใช้งาน
- https://dashboard.ngrok.com

2. กดFlok ที่Action ของนี่ แล้วไปที่Settings จากนั้นกดที่Secrets เพื่อสร้าง"Action Secrets" การสร้างให้ทำตามนี้
- กด"New repository secret"
- ช่องแรกให้ใส่ [ NGROK_AUTH_TOKEN ] *ไม่ต้องใส่ปีกกา ให้คัดลอกแค่ข้างในปีกกา
- ช่องที่สองให้เข้าลิ้งค์นี้ [ https://dashboard.ngrok.com/auth/your-authtoken ] แล้วคัดลอกAuth Token มาใส่ในช่องที่สอง 
- กดAdd secret
- กดAction แล้วเลือก"Select Workflow" จากนั้นเลือกที่"NAM_RDP"
- จากนั้นกดRun Workflow ถ้ายังไม่ขึ้นให้กดอีกรอบ ไม่ก็รีโหลดใหม่อีกรอบจนขึ้น จากนั้นเข้าไปแล้วกดที่"build" ได้เลย

3. IP, UserName, Password การเข้าใช้งานจะอยู่ที่Connect to Nam_RPD. แต่ต้องรอให้มันRun เสร็จก่อน

**มีปัญหาแจ้งที่เฟซบุ๊คส่วนตัว หรือไลน์ก็ได้นะครับ**
Facebook: https://www.facebook.com/rutchawat

Line: @shickie__2331

*zxlxctor.*
