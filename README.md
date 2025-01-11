# **Django CRM System - Internship Project**

### **Overview**
This is a Django-based Customer Relationship Management (CRM) system developed as part of the Youvah Internship Week 1 project. The application is designed to help businesses manage:
- Customer data and interactions
- Business information
- Sales and marketing automation
- Customer support
- Relationships with employees, vendors, and partners

---

### **Features**
- Superuser login and logout functionality.
- Modular structure for managing different aspects like customers, sales, and employees.
- Static files and templates configured for better UI and customization.
- Easy-to-extend and maintain Django architecture.

---

### **Project Setup**
Follow these steps to set up the project on your local machine:

#### **1. Prerequisites**
- Python 3.9 or higher installed
- Git for version control
- A virtual environment for isolating dependencies

#### **2. Installation Steps**
1. Clone the repository:
   ```bash
   git clone https://github.com/your_username/Youvah_Internship_Project_Week_1.git
   cd Youvah_Internship_Project_Week_1
   ```

2. Set up a virtual environment:
   ```bash
   python -m venv env
   source env/bin/activate   # On Windows: env\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Run migrations to set up the database:
   ```bash
   python manage.py migrate
   ```

5. Create a superuser:
   ```bash
   python manage.py createsuperuser
   ```

6. Start the development server:
   ```bash
   python manage.py runserver
   ```

7. Access the application in your browser:
   - Admin Panel: `http://127.0.0.1:8000/admin/`
   - Home Page: `http://127.0.0.1:8000/`

---

### **Project Structure**
```
Youvah_Internship_Project_Week_1/
├── varlyq/                 # Core Django project files
│   ├── settings.py         # Project settings
│   ├── urls.py             # Main URL configuration
│   ├── ...
├── dcrm/                   # App for CRM functionalities
│   ├── templates/          # HTML files
│   ├── static/             # Static files (CSS, JS, Images)
│   ├── views.py            # App views
│   ├── ...
├── templates/              # Project-level templates
├── static/                 # Project-level static files
├── manage.py               # Django CLI utility
└── requirements.txt        # Project dependencies
```

---

### **Technologies Used**
- **Framework:** Django
- **Frontend:** HTML, CSS
- **Backend:** Python
- **Database:** SQLite (default)

---

### **How to Contribute**
1. Fork the repository.
2. Create a feature branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add feature-name"
   ```
4. Push to the branch:
   ```bash
   git push origin feature-name
   ```
5. Create a pull request.

---

### **Contact**
For questions or feedback, feel free to reach out:
- **Email:** cainebenoy@gmail.com
- **GitHub:** [cainebenoy]([https://github.com/your_username](https://github.com/cainebenoy))
