# Customer Relationship Management System(CRM)
## **Project Name:** FIN-AUDIT

### **Abstract:**

Fin-Audit is a specialized Customer Relationship Management system tailored for fintech companies. It employs Python, Django, MySQL, React.js, and AWS to offer a robust suite of features. This includes secure user authentication, role-based access control, and compliance with regulatory standards. The software enables detailed customer profile management, tracking of financial transactions, and seamless communication with customers. It also provides advanced analytics and reporting, task management, and calendar functions. Integration with AWS ensures data security and scalability. The system includes modules for customer onboarding, managing financial products, customer support, targeted marketing campaigns, and compliance tracking. Fin-Audit is designed to streamline customer relations and data management in the dynamic world of fintech.

### **Technology used:**

- **Backend:** Python, Django, DRF, Celery, Boto3, MySQL, SQLAlchemy <br>
- **Frontend:** React.js, JavaScript, HTML5, CSS3, Bootstrap <br>
- **Data Processing:** Numpy, Pandas, Matplotlib <br>
- **Deployment and Storage:** AWS (EC2, S3) <br>
- **Templates:** Jinja2

### **Actual Role:**

- Writing scalable Python codes related to User Management and Customer Profile modules using Django framework. <br>
- Using ORM technique to connect with MySQL database. <br>
- Used REST API to perform CRUD operations for Data Management. <br>
- Implemented SQL-Alchemy for database interaction. <br>
- Utilized Pandas and Numpy for data cleaning and transformation. <br>
- Developed frontend components using React.js for a responsive user interface.

**Django:**

Django is a macro framework. It is an open-source web framework for building web applications using Python. It emphasizes rapid development by providing tools for handling database interactions, URL routing, and templates. Django's ORM simplifies database operations, while its URL dispatcher helps manage URL patterns. It encourages clean code separation through templates, supports user authentication and authorization, and offers a built-in admin interface for managing application data. Django also includes security features and internationalization support, making it a powerful and efficient choice for web development.

### **Functionality:**

- **User Authentication and Authorization:** Creation of user accounts, authentication, and authorization. <br>
- **Customer Data Management:** Storing and organizing customer information including personal details, financial profiles, transaction history, and communication preferences. <br>
- **Transaction Tracking:** Recording all customer transactions for compliance, audit, and customer support. <br>
- **Communication Tools:** Email integration, chat, and notification systems for customer communication. <br>
- **Reporting and Analytics:** Generating reports and providing analytics on customer behavior and system performance. <br>
- **Task Management:** Assigning and tracking tasks related to customer inquiries and follow-ups. <br>
- **Compliance and Audit Tools:** Conducting compliance checks, maintaining audit trails, and ensuring regulatory compliance. <br>
- **Integration with Financial Data Sources:** Enriching customer profiles and transaction information with external data sources. <br>
- **Document Management:** Securely storing and managing customer-related documents.

### **Modules:**

- **User Management:** Handles user roles and permissions, user registration, access control, and user profile management. <br>
- **Customer Profile:** Manages customer details, including personal information, financial data, transaction history, and communication preferences. <br>
- **Transaction History:** Tracks all financial transactions associated with each customer. <br>
- **Communication Module:** Manages customer interactions, including emails, chat logs, and notifications. <br>
- **Reporting and Analytics Module:** Generates reports, dashboards, and analytics based on CRM data. <br>
- **Task Management Module:** Assigns, tracks, and completes tasks related to customer inquiries and follow-ups. <br>
- **Compliance and Audit Module:** Conducts compliance checks, maintains audit logs, and ensures regulatory compliance. <br>
- **Integration Module:** Connects with external data sources and APIs to update customer records. <br>
- **Document Management Module:** Handles the storage and organization of customer-related documents.

### **Packages and Libraries:**

- **Django:** Core web framework providing user authentication, database management, and URL routing. <br>
- **MySQL Database Connector:** Mysqlclient or Django's built-in database connector for interacting with MySQL. <br>
- **Django REST Framework:** Facilitates API development, including serializers and viewsets. <br>
- **Boto3:** Interacts with AWS services for tasks like managing S3 buckets and EC2 instances. <br>
- **Celery:** For asynchronous task processing, such as email notifications and report generation. <br>
- **Django Channels:** Extends Django to handle asynchronous protocols and real-time communication. <br>
- **Pandas:** For data manipulation and analysis. <br>
- **NumPy:** For mathematical and numerical operations. <br>
- **Matplotlib:** For data visualization and creating financial charts and reports. <br>
- **Django Allauth:** Advanced authentication and account management. <br>
- **Django Filter:** Creates advanced filtering and search capabilities. <br>
- **AWS SDKs:** AWS SDK for Python (Boto3), AWS SDK for JavaScript for front-end integration. <br>
- **PyJWT**: Manages JSON Web Tokens for secure API access.

### **ORM used in this project:**

Used MySQL database and SQLAlchemy for managing and manipulating relational databases, providing a flexible and scalable solution for data management.

### **Middleware:**

- **Django's Built-in Middleware:** Authentication, Session, Security, and CommonMiddleware. <br>
- **Custom Middleware:** Logging and auditing, user-specific operations, and CORS handling. <br>
- **Third-party Middleware:** Django REST framework middleware, caching, and database optimization. <br>
- **AWS Middleware:** AWS-specific middleware or services to optimize performance, security, and scalability. 

### **Issue faced in the project:**

**Third-party data integration issue:** Difficulties in adding third-party details like customer payment information into the database. <br>
**Steps taken to resolve:** <br>
- Error Identification and Logging <br>
- Isolating the Root Cause <br>
- Third-Party Integration Validation <br>
- Data Format and Validation <br>
- Data Integrity Checks <br>
- Error Handling and Logging Improvement <br>
- Data Migration (if required)

### **Deployment:**

Deployed on AWS using Amazon EC2 for deployment and AWS S3 for storage. EC2 provides scalable compute capacity, making it easy to deploy and manage applications.

