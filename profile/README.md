What is it?
-----
MUJ QAC Portal is a web application which is used by the Quality Assurance and Control department of Manipal University Jaipur. It is used to collect large amounts of data from different internal teams for QAC purposes of the university. 


How it works?
-----
User accounts are created for faculty members which can be labelled using tags to create different teams. Based on the data to be collected, a KPI is created by defining the columns and their datatypes. A KPI is basically a template Excel Sheet with custom validations built in. A KPI can be made avalaible to the faculty memebers from any team using the before mentioned tags. When the teams download the templete sheet and fill in the required details, they can upload the sheets on the same portal. The KPI creator can accept and merge the data to the master sheet by a single click. They can also reject the data submitted by any faculty member and mention a comment to state the reason of rejection. All the data collected is stored in different excel sheets in separate folders in the AWS S3 Bucket and therefore can be easily exported to further process it.


Data Flow
---
![dfd](https://user-images.githubusercontent.com/39013115/178792443-53bd09dd-9d93-4189-a95e-7a34b974779e.png)

TECHNOLOGIES USED
-----------------
* [TypeScript](https://www.typescriptlang.org/)
* [Node](https://nodejs.org/)
* [Express](https://expressjs.com/)
* [PostgreSQL](https://www.postgresql.org/)
* [AJV](https://ajv.js.org/)
* [PassportJS](https://www.passportjs.org/)
* [AWS SDK](https://aws.amazon.com/sdk-for-javascript/)
* [TypeORM](https://typeorm.io/)
* [Node XLSX](https://www.npmjs.com/package/node-xlsx)

Maintainers
-----------
Current maintainers: 
 * Vaibhav Garg [(dustspeck)](https://github.com/dustspeck)
 * Ayush Agrawal [(Lucifer0x17)](https://github.com/Lucifer0x17)
 * Arjun Aghera [(ArjunAghera)](https://github.com/ArjunAghera)
 * Omkar Dave [(Omkar31001)](https://github.com/Omkar31001)
 * Snehal Raj [(DarkShark-RAz)](https://github.com/DarkShark-RAz)

Screenshots
-----------
### View all KPIs
![View all KPIs](https://user-images.githubusercontent.com/39013115/178781457-dd1494f7-8c4d-4c59-800d-e3aae59c1cf1.jpg)
### Verify a KPI
![Verify a KPI](https://user-images.githubusercontent.com/39013115/178781462-43ec8d38-6c9f-46f0-99d9-ba350d8e96ab.jpg)
### Create new KPI
![Create new KPI](https://user-images.githubusercontent.com/39013115/178781465-8fe372bb-5c24-4d34-a9a4-2ae4dd83f01a.jpg)
### Set KPI Validations
![Set KPI Validations](https://user-images.githubusercontent.com/39013115/178781464-b19d582e-5c70-478e-94f7-49b4afe48fd3.jpg)
### Manage KPIs
![Manage KPIs](https://user-images.githubusercontent.com/39013115/178781470-b4c0eb96-21c2-4eca-8a5b-eb2811160f76.jpg)
### Manage Users
![Manage Users](https://user-images.githubusercontent.com/39013115/178781471-624c5f9f-8040-4654-8306-e349cf13fa9c.jpg)

