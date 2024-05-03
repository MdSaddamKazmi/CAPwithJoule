# CAPwithJoule

* Setup the Build code in your BTP account by following steps in https://developers.sap.com/tutorials/build-code-setup.html

![image](https://github.com/MdSaddamKazmi/CAPwithJoule/assets/54942497/8e388d92-8214-4f4e-812b-bba233ab7081)
![image](https://github.com/MdSaddamKazmi/CAPwithJoule/assets/54942497/8fe42a99-fa18-4153-821e-76b55dcbcb99)
![image](https://github.com/MdSaddamKazmi/CAPwithJoule/assets/54942497/bb2a8d77-fa13-4c5c-9aac-a6b2934320bf)
![image](https://github.com/MdSaddamKazmi/CAPwithJoule/assets/54942497/7de786b1-7926-4374-8a12-79a8cdc55882)
![image](https://github.com/MdSaddamKazmi/CAPwithJoule/assets/54942497/3ada25c3-0b9c-4b15-9314-4b0f251f6ef3)
![image](https://github.com/MdSaddamKazmi/CAPwithJoule/assets/54942497/62c52bcc-d90b-4704-8225-5bdac3fe544d)
![image](https://github.com/MdSaddamKazmi/CAPwithJoule/assets/54942497/e38a0004-004d-41a9-972c-298333ded1d9)

Design a School and Student detail application. 
Namespace is StudentDetails.
Define 2 data entities: School and Student. 
Both the entities have managed aspect derived from @sap/cds/common
Each Student must have the following fields: student_id, firstName, lastName, dateOfBirth, dateOfJoining ,email, phoneNumber.
for each student, field student_id is the key field.
for each student, field student_id will be Integer.
for each student, fields firstName, lastName, email and phoneNumber will be String.
for each student, fields dateOfBirth and dateOfJoining will be Date type.
for each student, fields student_id, firstName and phoneNumber will have mandatory annotation.
Each student will have association to one school and association is called school and it is readonly.

Each school should have a school_id, SchoolName, Principal, SchoolStrength, Curriculum and rating.
for each school, field school_id is the key field.
All fields for each school should be String except school_id and SchoolStrength that will be stored as Integer. 
for each school, fields school_id, SchoolName, Principal and Curriculum have mandatory validation.
for each school, field SchoolStrength is readonly and field rating has range of enum in A , B and C
Each school will have composition of many students and composition is called students and it is readonly.

![image](https://github.com/MdSaddamKazmi/CAPwithJoule/assets/54942497/cb26e85f-11d0-4b91-97ee-462c811a10bb)
Click on Accept.

![image](https://github.com/MdSaddamKazmi/CAPwithJoule/assets/54942497/10c1aa13-d89c-4591-9927-f7a5e6ee23e3)

In the Storyboard, click on the School entity under Services, and select Open in Graphical Modeler.

![image](https://github.com/MdSaddamKazmi/CAPwithJoule/assets/54942497/97a20238-5f2d-4e33-94d2-4317f983723c)
![image](https://github.com/MdSaddamKazmi/CAPwithJoule/assets/54942497/3f5e2544-171a-451a-8ebd-33989ae05380)
![image](https://github.com/MdSaddamKazmi/CAPwithJoule/assets/54942497/10aa8cfe-986e-4bfa-94ac-5afd0cefd255)

Assign the length of students array in that school to the schoolstength field of school. 
If email field of student is blank then add firstname , lastname and @gmail.com and assign to email.

![image](https://github.com/MdSaddamKazmi/CAPwithJoule/assets/54942497/7f02d93c-92c4-43d2-9392-47785bfce1a8)
Try to Regenerate and check if you get another code.
![image](https://github.com/MdSaddamKazmi/CAPwithJoule/assets/54942497/8ce2d27c-7101-47ed-9ef6-4d2b07f4ca8a)
![image](https://github.com/MdSaddamKazmi/CAPwithJoule/assets/54942497/ed7d8518-9ec9-4628-8dcf-599920e81917)

Create UI with main entity as "School".
![image](https://github.com/MdSaddamKazmi/CAPwithJoule/assets/54942497/16393083-bfcd-493a-8ee8-ec3aca2a97fe)

To preview your application, once the files have been generated, go to the upper-right corner, and click preview (Run and Debug).
The preview will be as : 
![image](https://github.com/MdSaddamKazmi/CAPwithJoule/assets/54942497/3c625cb6-e7f3-421a-a5e0-f8f080ecc995)
CLick on the tile to open the app.


Reference : https://developers.sap.com/tutorials/build-code-test-drive.html














