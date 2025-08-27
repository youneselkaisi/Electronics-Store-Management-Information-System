# Electronics Store MIS
## Overview
This repository contains a live, scalable Management Information System built for a small electronics retail business. It uses Microsoft Access as the primary front-end and data store, Excel for exports and ad-hoc analysis, and SQL for robust querying and optional backend scaling; the system supports core business entities including employees, customers, suppliers, inventory, sales and invoices and delivers practical analytic capabilities such as sales summaries, profit and loss reports, payroll listings and date-filterable financial views. It is also designed for real operational use with continuous updates (new products, customers, transactions) rather than a static demo. 

## Files

The Repository contains 2 versions of the MIS:
1. "Dev" file contains all objects (tables, forms, reports, queries) for viewing. Useful for understanding what's happening in the background and for viewing the data model
2. "Live" file is the production-ready file. All objects and menus are hidden, and all additional records must be added via the forms.

## Instructions 

**Username:** "mohawk"


**Password:** "123"

**Reports:** start/end date input "January,2024" (no spaces) -> format is "MMMM,YYYY", this can be changed in the Dev file under "apps" in the queries section if desired


## Process  

- Raw data files (Customers, Suppliers, Inventory, Employees, etc.) were provided by **Professor James Fowler**.  
- The relational data model was designed and planned using [drawsql.app](https://drawsql.app/).  
- Data was loaded into **Microsoft Access** from Excel sheets, and the schema was fully implemented.  
- Custom **forms** were built, including *Item Master, Suppliers, Vendors, and Customers*, for user-friendly data entry.  
- Advanced **reports** were developed for **Payroll**, **Sales & Profit Analysis**, and **Customer Search**, utilizing SQL queries.  
- A **login form** with Username and Password authentication was coded.  
- Final formatting and polishing were completed to make the system user-ready.


## Use Cases  

- **Small Businesses & Retail Shops** – Can use the system as a lightweight alternative to expensive ERP solutions.  
- **Sales & Payroll Reports** – Managers can quickly generate reports for sales performance, payroll accuracy, and profit analysis.  
- **Customer & Supplier Management** – Easy tracking of ongoing relationships with suppliers, vendors, and customers.  
- **Inventory Tracking** – Ensures stock levels are monitored and adjusted in real time.  
- **Extensible Design** – New modules (purchase orders, employee scheduling, tax reporting, etc.) can be added with minimal effort.  
- **Scalability** – Suitable for a single shop or an expanding chain, due to clean relational modeling and structured database design.  
- **Academic to Real-World Bridge** – Demonstrates how classroom learning (Excel, Access, SQL) can be applied to real business impact.  
- **Future Enhancements** – Can be integrated with web dashboards, mobile apps, or cloud-based analytics services.

  ## MIS Showcase

**Login Page**
<img width="1204" height="544" alt="image" src="https://github.com/user-attachments/assets/34c0f994-2c21-4412-b9ad-54cfdd990300" />

**Data Model**
  
  <img width="1782" height="629" alt="image" src="https://github.com/user-attachments/assets/77eb5bb5-4c5b-4ddf-b07c-ea2e1f766ca0" />


**Homepage**

<img width="840" height="615" alt="image" src="https://github.com/user-attachments/assets/39a5b2dc-7e0d-4738-865d-702ce6ea6955" />

**Customer Form**

<img width="1194" height="623" alt="image" src="https://github.com/user-attachments/assets/bd805efc-5428-4e4a-8c05-83a2bef4d946" />

**Invoice Form**

<img width="1504" height="623" alt="image" src="https://github.com/user-attachments/assets/e1097627-5f85-4f4a-9a18-d3f82ffa2bba" />


**Voucher Form**

<img width="1449" height="617" alt="image" src="https://github.com/user-attachments/assets/80e42d51-c2e3-4a83-832b-a2621bb17c3b" />


**Customer Search**

<img width="776" height="133" alt="image" src="https://github.com/user-attachments/assets/ac6b8678-c928-4b7c-88e4-a32d4ae8b567" />


**Sales-Profit Report**

<img width="1534" height="605" alt="image" src="https://github.com/user-attachments/assets/635002c1-8b69-459e-a49c-14584e50b90b" />

**Payroll Report**

<img width="1202" height="459" alt="image" src="https://github.com/user-attachments/assets/9e7b525b-7353-4a8a-88d0-61ba403c8ddc" />

**Payroll app SQL**

<img width="1211" height="659" alt="image" src="https://github.com/user-attachments/assets/30b23792-5b5b-41c4-b0ad-6faa23f71214" />


## Conclusion

This project demonstrates how Microsoft Access, Excel, and SQL can be integrated to build a functional business management system capable of handling sales, payroll, and customer reporting. By designing the data model, creating interactive forms, and generating automated reports, the system highlights the potential of accessible database tools for real business needs. Through this process, I gained hands-on experience in database design, SQL query building, and form/report development, which deepened my understanding of how data can be organized and transformed into actionable insights. Overall, the project not only provided a practical solution but also strengthened my technical and problem-solving skills.


## Acknowledgments

- Professor James Fowler — for providing the data files and guiding us step by step through the process.





