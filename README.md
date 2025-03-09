
# Project Title- 👨‍💼 Employee Record Management System



## 🚀 Technolonlgies Used-
 


- 🖥️ **Backend**: ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
- 🎨 **Frontend**: ![HTML](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white) ![CSS](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=flat-square&logo=bootstrap&logoColor=white)
- 🗄️ **Database**: ![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)



---

## 📌 Overview  

The **Employee Record Management System** is a **Django-based** web application designed to help organizations **store, manage, and track employee details** efficiently. It provides **secure login, record management, and data export** for HR teams.  

---

## 🚀 Features  

### 📝 **Personal Details Management**  
📂 Store and manage **employee personal details**, including:  
- 👤 **Name**  
- 🎂 **Birth Date**  
- 📞 **Contact Details**  
- 🏢 **Current Department & Designation**  
- 📅 **Joining Date**  
- 🚻 **Gender**  

---

### 🎓 **Educational Information Management**  
📖 Capture and manage **educational qualifications**, including:  

✅ **Graduation and Post Graduation Details**  
   - 📊 **Marks**  
   - 📅 **Passing Year**  
   - 🏛️ **College Name**  

✅ **Higher Secondary Certificate (HSC) Details**  
   - 📊 **Marks**  
   - 📅 **Passing Year**  
   - 🏫 **School/College Name**  

✅ **Secondary School Certificate (SSC) Details**  
   - 📊 **Marks**  
   - 📅 **Passing Year**  
   - 🏫 **School/College Name**  

---

### 💼 **Professional Experience Management**  
📋 Record and manage **past work experiences**, including:  
- 🏢 **Company Name**  
- 💰 **Salary**  
- ⏳ **Job Duration**  
- 👔 **Designation**  
- 🏬 **Department**  

---

### 🔧 **Admin Capabilities**  
👨‍💼 **Administrators** have **full control** over employee records:  
- ✏️ **Edit, update, or delete employee details**  
- ✅ **Ensure data accuracy and consistency**  

---

### 📂 **Data Export & Conversion**  
📄 Export employee details to multiple formats:  
- 📝 **PDF**  
- 📊 **Excel**  
- 📜 **CSV**  

---
 




## 📸 Screenshots  
## 🛠️ Admin Login
![admin photo](https://github.com/user-attachments/assets/e11a5e31-f8cc-484c-aa86-948ba895bc60)

### 🏢 **Admin Portal**  
![Admin Portal](https://github.com/user-attachments/assets/1e96b2c2-7d4b-42fa-95b9-9eb5186e463f)  

### 📌 **Admin Dashboard**  
![Admin Dashboard](https://github.com/user-attachments/assets/f1d26da3-644d-49e0-ae9c-ebe2ff473dd0)  

### 👨‍💼 **Employee Dashboard**  
![Employee Dashboard](https://github.com/PranavKulkarnipy/Employee-Record-Management-System/assets/156565305/adaf29f7-b227-4b3b-8bff-c90502c52f8b)  

### 🆔 **Employee Profile**  
![Employee Profile](https://github.com/PranavKulkarnipy/Employee-Record-Management-System/assets/156565305/01c1ebaf-243e-43ce-928d-bbf17444d6e8)  

### 💼 **Work Experience Interface**  
![Experience](https://github.com/PranavKulkarnipy/Employee-Record-Management-System/assets/156565305/5177314d-136a-4037-81cb-9dda9ed4379c)  

### 🎓 **Education Interface**  
![Education](https://github.com/PranavKulkarnipy/Employee-Record-Management-System/assets/156565305/0d2fa689-9b69-4c52-876a-f4cf239994a8)  

### 📝 **Employee Signup Page**  
![Employee Signup](https://github.com/PranavKulkarnipy/Employee-Record-Management-System/assets/156565305/28bf274b-e2c3-49ad-a436-33ad778bb876)  

### 🏠 **Home Interface**  
![Home Interface](https://github.com/PranavKulkarnipy/Employee-Record-Management-System/assets/156565305/f57a6741-4438-40b6-923b-119a45dacb2e)  

---
# 📥 Installation Guide  

🚀 Follow the steps below to set up and run the **Employee Record Management System** on your local machine.

## 📥 **Step 1: Clone the Repository**  

Clone the project from GitHub to your local machine:  

```bash
git clone https://github.com/PranavKulkarnipy/Employee-Record-Management-System.git
```

Navigate to the project directory:  

```bash
cd Employee-Record-Management-System
```

---

## 🏗️ **Step 2: Create a Virtual Environment**  

💡 *Creating a virtual environment ensures dependencies are managed properly.*  

```bash
python -m venv venv
```

### ▶️ **Activate Virtual Environment**  
For **Windows**:  
```bash
venv\Scripts\activate.bat
```

For **Mac/Linux**:  
```bash
source venv/bin/activate
```

---

## 🔧 **Step 3: Install Required Dependencies**  

Install Django and other dependencies:  

```bash
pip install django
```

---

## 📂 **Step 4: Navigate to the Project Directory**  

```bash
cd EmployeeRecordMgmt
```

---

## 🔑 **Step 5: Create a Superuser (Admin Access)**  

Create an admin user to manage employee records:  

```bash
python manage.py createsuperuser
```

📌 *You will be prompted to enter a username, email, and password.*  

---

## 🚀 **Step 6: Run the Development Server**  

Start the Django server:  

```bash
python manage.py runserver
```

📌 **By default, the application runs on:**  
🔗 **http://127.0.0.1:8000/**  

---

## 🛠️ **Step 7: Access the Admin Panel**  

1️⃣ Open your browser and visit:  
   🔗 **http://127.0.0.1:8000/admin/**  

2️⃣ Login using the **superuser credentials** created earlier.

✅ **You can now start managing employee records!** 🎉  

---

## 📌 **Installation Summary**  

| **Step** | **Command** |
|----------|------------|
| 🛠️ Clone Repository | `git clone https://github.com/PranavKulkarnipy/Employee-Record-Management-System.git` |
| 🌍 Navigate to Directory | `cd Employee-Record-Management-System` |
| 🏗️ Create Virtual Environment | `python -m venv venv` |
| ▶️ Activate Virtual Environment (Windows) | `venv\Scripts\activate.bat` |
| ▶️ Activate Virtual Environment (Mac/Linux) | `source venv/bin/activate` |
| 🔧 Install Django | `pip install django` |
| 📂 Navigate to Project Directory | `cd EmployeeRecordMgmt` |
| 🔑 Create Superuser | `python manage.py createsuperuser` |
| 🚀 Run Server | `python manage.py runserver` |
| 🛠️ Open Admin Panel | `http://127.0.0.1:8000/admin/` |

---

## 🎯 **Congratulations!** 🎯  

Your **Employee Record Management System** is now successfully installed and running! 🚀  

⭐ **Star the repository** on GitHub if you found it useful! 😊  



