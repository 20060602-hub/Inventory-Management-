
#  Sales and Inventory Management System

A comprehensive **Django-based web application** that automates inventory, sales, product, vendor, and user management. This system helps businesses improve efficiency, track data accurately, and reduce manual overhead through a centralized digital solution.

---

##  Table of Contents

- [Project Overview](#project-overview)
- [Business Requirements & Functionalities](#business-requirements--functionalities)
- [Tech Stack](#tech-stack)
- [Installation Instructions](#installation-instructions)
- [ Introduction](#-introduction)
- [ Abstract](#-abstract)
- [ Objective](#-objective)
- [ Functionalities](#-functionalities)
- [ Scope](#-scope)
- [ Reports](#-reports)
- [ Modules](#-modules)
- [ Features](#-features)
- [ Tools, Platform & System Requirements](#️-tools-platform--system-requirements)
- [ Tech Stack](#️-tech-stack)
- [ Installation Instructions](#-installation-instructions)
- [ Usage Guide](#-usage-guide)
- [ Screenshots](#-screenshots)
- [ Code Snippets & Configuration](#-code-snippets--configuration)
- [ References & Bibliography](#-references--bibliography)
- [ Deployment](#-deployment)
- [ Future Enhancements](#-future-enhancements)
- [ Attributions](#-attributions)
- [ License](#-license)
- [Contact](#-contact)

##  Project Overview

The **Sales and Inventory Management System** aims to streamline operations by replacing error-prone manual processes with a robust web platform. Designed for use by admins and staff, it enables seamless tracking and reporting of inventory, vendors, orders, costs, and deliveries.

Built with Django and MySQL, it offers modular architecture, secure authentication, and modern UI elements to provide a smooth and intuitive user experience.

---

##  Business Requirements & Functionalities

###  Authentication & User Management
- Admin login, logout, registration
- Role-based access (Admin, Manager, Staff)
- Profile update, password change, session handling

###  Inventory Management
- CRUD operations on inventory
- Live stock quantity updates
- Inventory alerts on low quantity

###  Product and Cost Tracking
- Product management with dynamic pricing
- Cost tracking per vendor
- Product categorization

###  Order and Delivery Management
- Order creation, update, status tracking
- Delivery status and historical records
- Export options: PDF, CSV, Excel

###  Vendor Management
- Vendor registration and management
- Vendor-product-cost linkage
- Vendor contact and rating system (future)

###  Reporting & Export
- Reports: Inventory, Vendor, Orders, Costs
- Export in multiple formats
- Visual reports (future scope)

###  Data Integrity and Validation
- Robust form validations
- Input sanitization and CSRF protection
- Error messaging and redirection handling

---

##  Tech Stack

| Layer           | Technology                |
|----------------|---------------------------|
| Frontend       | HTML5, CSS3, Bootstrap     |
| Backend        | Python 3.x, Django         |
| Database       | MySQL                      |
| Server         | Django Dev Server          |
| Compatibility  | Windows / Linux / macOS    |

---

##  Installation Instructions

###  Prerequisites
- Python 3.x installed
- MySQL Server running
- Git and pip installed

###  Setup Steps

```bash
# Clone the repository
git clone https://github.com/yourusername/sales-inventory-management-system.git
cd sales-inventory-management-system

# Create and activate virtual environment
python -m venv venv
source venv/bin/activate   # Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Configure database
# Create a MySQL database named 'sales_inventory_management_system'
# Update the credentials in settings.py

# Apply migrations
python manage.py makemigrations
python manage.py migrate

# Create superuser (optional)
python manage.py createsuperuser

# Run the development server
python manage.py runserver
```

---

##  Usage Guide
- Login via `/login`
- Use the dashboard to access Inventory, Vendors, Orders
- Use the export options to download data
- Admins can manage users from the admin panel

---



---



##  Introduction

The "Sales and Inventory Management System" has been developed to override the problems prevailing in the practicing manual system. It reduces errors in data entry, ensures smooth company operations, and is user-friendly even for non-technical users. This system is aimed at improving operational efficiency and reducing overhead by offering centralized, fast, and secure management tools.

This application supports executives with remote access, enabling workforce and operations management at all times.

---

##  Abstract

The purpose of this system is to automate existing manual processes using computer software and hardware. This ensures long-term data storage with easy access and manipulation, increased reliability, reduced redundancy, and optimal resource use.

---

##  Objective

To manage and streamline the details of:
- Inventory
- Vendor
- Product
- Cost
- Orders
- Delivery

The application centralizes all data under the administrator role and minimizes manual work by offering real-time information tracking and efficient data handling features.

---

##  Functionalities

-  Search based on Inventory, Product, Cost, and Orders
-  Track and manage Delivery details online
-  Vendor and Cost detail management
-  Update, edit, and manage Inventory records
-  Full integration of Order and Cost modules

---

##  Scope

This project aims to automate business processes, provide quick access to historical and current data, and generate documentation and forms at scale. It assists in:

- Efficient resource utilization
- Accurate data entry and reporting
- Easy-to-use interface with high scalability
- Reduced operational costs and paperwork
- Time-efficient workflow automation

---

##  Reports

-  Generates reports for Inventory, Vendor, and Delivery
-  Filterable reports for Product, Cost, and Order
-  Export options:
  - PDF: Inventory, Delivery, Cost
  - Excel: Vendor, Product, Order
  - CSV: Inventory, Vendor, Order

---

##  Modules

- **Inventory Management** – Tracks all inventory items and updates
- **Order Management** – Creates and updates customer order info
- **Delivery Management** – Manages delivery and shipment records
- **Vendor Management** – Tracks vendor contact and supply details
- **Product Management** – Catalogs product data and pricing
- **Cost Management** – Monitors cost inputs for products and vendors
- **Login Module** – Handles authentication securely
- **User Management** – Adds/updates users and assigns roles


---

##  Features

The Sales and Inventory Management System offers a comprehensive feature set to simplify and streamline organizational processes:

-  **Product and Component based design**
-  **Create and modify issues easily** with clear tracking
-  **Query issue list with deep filtering**
-  **Advanced reporting and charting** for better insights
-  **User accounts** to manage access levels and enhance security
-  **Simple status and resolution tracking**
-  **Multi-level priority and severity support**
-  **Targets and milestones** to guide progress and team productivity
-  **Attachments and comments** for context-rich records
-  **Robust database back-end** for reliable data handling
-  **Filterable, multi-level reports** with numerous criteria
-  **Improved storage capacity** for data and logs
-  **High accuracy in data handling**
-  **Fast and easy data retrieval**
-  **Professionally designed reports**
-  **Reduces workload** in manual tracking
-  **Instant access** to any information
-  **Speeds up operations** and workflow
-  **Easy updating** of existing records

---


---

##  Tools, Platform & System Requirements

This system was developed and tested using the following tools and platform configurations:

###  Software Requirements

| Component                | Specification                                 |
|--------------------------|-----------------------------------------------|
| Operating System         | Windows 98 / XP / 7, or Linux                 |
| Programming Language     | Python                                        |
| Database                 | MySQL Server                                  |
| Browser Compatibility    | Mozilla Firefox, Opera, Google Chrome, etc.  |
| Web Framework            | Django                                        |
| Software Development Kit| Visual Studio                                 |

###  Hardware Requirements

| Component     | Specification         |
|---------------|------------------------|
| Processor     | Pentium III 630 MHz    |
| RAM           | 128 MB                 |
| Hard Disk     | 20 GB                  |
| Monitor       | 15” Color Monitor      |
| Keyboard      | 122 Keys               |

---


---

##  Code Snippets & Configuration

This project is built using Django with a modular MVC architecture. Below is an overview of the coding structure and settings configuration used in the Sales and Inventory Management System.
<img width="959" alt="image" src="https://github.com/user-attachments/assets/311f185f-8111-4cd0-9eb2-211136cb87f0" />
Home page 
<img width="959" alt="image" src="https://github.com/user-attachments/assets/8c985ce6-f5d7-4cc9-8ffe-c35fdd4a9bd8" />
System Admin Page
<img width="951" alt="image" src="https://github.com/user-attachments/assets/d61de2d7-7518-406e-96b9-75caacffcf5f" />
DashBoard
<img width="959" alt="image" src="https://github.com/user-attachments/assets/de8a25d3-9543-4eb6-8911-0c78fb1f59e8" />
Product details
<img width="959" alt="image" src="https://github.com/user-attachments/assets/9da8102d-5049-432d-8a18-52efb1d0daf8" />
Sales Page
<img width="959" alt="image" src="https://github.com/user-attachments/assets/7db467f6-304f-4360-9568-24ba49a7e17c" />
Shopping Cart 
<img width="959" alt="image" src="https://github.com/user-attachments/assets/d3a7fb4a-4d37-4e0e-b677-c6731a3ebeb2" />
Customer Information
<img width="959" alt="image" src="https://github.com/user-attachments/assets/80ab5554-372c-4eb7-a988-5f147f361bfb" />
Order details and payments
<img width="958" alt="image" src="https://github.com/user-attachments/assets/6c255ce5-d202-4a33-b0cd-e688bef0b67f" />

Print Receipt
<img width="959" alt="image" src="https://github.com/user-attachments/assets/98135ff5-0cd8-4e7e-a6b3-1234b51157bb" />
Inventory Report
<img width="959" alt="image" src="https://github.com/user-attachments/assets/571c6c3a-74fd-4ef3-8786-cda7b2ca5977" />
Order Report
<img width="959" alt="image" src="https://github.com/user-attachments/assets/459b7b7b-98f4-4e85-857a-25a673c1a488" />
Order Recepits and details

###  Views Example (`views.py`)
```python
def listing(request):
    cursor = connection.cursor()
    cursor.execute("SELECT * FROM company")
    companylist = dictfetchall(cursor)
    context = { "companylist": companylist, "heading": "Company Details" }
    return render(request, 'company-details.html', context)
```

###  URL Routing (`urls.py`)
```python
urlpatterns = [
    url(r'^$', views.listing, name="company-listing"),
    url(r'^add$', views.add, name="add"),
    url(r'^update/(?P<companyId>\w{0,50})/$', views.update, name="update"),
    url(r'^delete/(?P<id>\w{0,50})/$', views.delete, name="delete"),
]
```

### ⚙️ Django Settings Highlights (`settings.py`)
```python
DATABASES = {
    'default': {
        'ENGINE': 'mysql.connector.django',
        'NAME': 'sales_inventory_management_system',
        'USER': 'root',
        'PASSWORD': '',
        'HOST': '',
        'PORT': ''
    }
}

INSTALLED_APPS = [
    'users.apps.UsersConfig',
    'products.apps.ProductsConfig',
    'company.apps.CompanyConfig',
    ...
]

STATIC_URL = '/assets/'
MEDIA_URL = '/uploads/'
```

>  **Note:** These are code excerpts. For the full source code, see the project repository files.

---


---

##  References & Bibliography

The development of the Sales and Inventory Management System was supported by various online resources and learning materials:

- Google Search for troubleshooting and implementation tips
- [VB.NET Credential Review](http://www.vbnetworld.com/vbnetworld/jw-01-1998/jw-01-Credentialreview.html)
- *Database Programming with JDBC and VB.NET* by O'Reilly
- *Head First VB.NET*, 2nd Edition
- [JDBC Tutorial](http://www.jdbc-tutorial.com/)
- *VB.NET and Software Design Concepts* by Apress
- [TutorialsPoint – VB.NET](https://www.tutorialspoint.com/vbnet/)
- [VB.NET Tutorial](http://www.vbnettpoint.com/vbnet-tutorial)
- [Oracle VB.NET Tutorial](https://docs.oracle.com/vbnetse/tutorial/)
- [WAMP Server](http://www.wampserver.com/en/)
- [VB.NET Official](http://www.VBNET.net/)
- [MySQL Tutorial – TutorialsPoint](http://www.tutorialspoint.com/mysql/)
- [Apache HTTP Server Tutorials](http://httpd.apache.org/docs/2.0/misc/tutorials.html)

---

##  Deployment

Deployment can be done on:
- Heroku
- Render
- PythonAnywhere
- VPS with Apache/Nginx and Gunicorn

Make sure to:
- Set `DEBUG = False`
- Add allowed hosts
- Use environment variables for DB credentials and secret key
- Use `whitenoise` or S3 for static/media file handling

---

##  Future Enhancements

- Email/SMS alerts for low stock
- REST API with DRF for mobile integration
- Barcode scanning support
- Product image gallery
- Advanced analytics dashboard
- Cloud backups and logging

---

##  Attributions

This project uses open-source tools and tutorials:

- [Django](https://www.djangoproject.com/)
- [Bootstrap](https://getbootstrap.com/)
- Snippets from Stack Overflow and Django Docs
- Icons from FontAwesome
- MySQL Server from Oracle

**All reused or adapted code is credited and commented in code files.**

---

##  License

This project is licensed under the Vengalarao Danthuluri

---

##  Contact

**Maintainer**:  Vengalarao Danthuluri
**Email**: 20060602@mydbs.ie  
**GitHub**: https://github.com/20060602-hub/Sales-and-Inventory-Management-System/tree/master

