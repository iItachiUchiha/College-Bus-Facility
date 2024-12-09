
# College Bus Management System  

**College Bus Management System** is a web-based application designed to streamline and automate college transportation services. Built using **Django**, the system manages buses, drivers, routes, staff, and students with ease, ensuring efficient transportation operations within the college.  

---

## 🚀 Project Description  

The system simplifies and organizes various aspects of college transportation, including:  
- Managing buses, drivers, and routes.  
- Providing tailored dashboards for different user roles (admin, drivers, staff, and students).  
- Ensuring secure access through robust authentication, including social authentication with Google.  

With a focus on automation, scalability, and modern UI/UX, this project addresses the needs of college transportation management in a secure and user-friendly manner.  

---

## 🛠️ Technology Stack  

### **Backend**  
- **Framework**: Django  
- **Database**: SQLite  

### **Frontend**  
- **Languages**: HTML, CSS, JavaScript  
- **Frameworks**: Bootstrap  

### **Authentication**  
- Django authentication system  
- Social-auth-app-django for Google authentication  

### **Other Tools**  
- Dynamic URL routing  
- Form widgets for enhanced UI  

---

## ⚙️ Installation and Setup  

### **Prerequisites**  
- Python 3.8 or higher  
- Django 3.0 or higher  
- A web browser for testing  
- Virtual environment tool (optional but recommended)  

### **Setup Steps**  

1. **Clone the Repository**  
   ```bash  
   git clone https://github.com/YourUsername/College-Bus-Management.git  
   cd College-Bus-Management  
   ```  

2. **Create and Activate a Virtual Environment**  
   ```bash  
   python -m venv env  
   source env/bin/activate  # For Linux/Mac  
   env\Scripts\activate     # For Windows  
   ```  

3. **Install Dependencies**  
   ```bash  
   pip install -r requirements.txt  
   ```  

4. **Set Up the Database**  
   ```bash  
   python manage.py migrate  
   ```  

5. **Run the Server**  
   ```bash  
   python manage.py runserver  
   ```  

6. **Access the Application**  
   Open your browser and visit: `http://127.0.0.1:8000`  

---

## 🌟 Key Features  

### 1. **User Authentication and Authorization**  
- Secure authentication for role-based access (admin, driver, staff, student).  
- Google authentication for ease of access and enhanced security.  

### 2. **Bus Management**  
- Add, edit, view, and delete bus records.  
- One-to-One relationship for assigning drivers to specific buses.  

### 3. **Driver Management**  
- Manage driver details such as name, contact, license, and assigned buses.  
- Responsive Bootstrap forms for seamless interaction.  

### 4. **Route Management**  
- Add, modify, and manage route details like name, start and end points, and route numbers.  
- Easy navigation using dynamic URLs.  

### 5. **Staff Management**  
- CRUD operations for managing staff members.  
- Restricted access to ensure security.  

### 6. **Student Management**  
- Add, update, and manage student information like ID, course, and contact details.  
- Dynamic links for quick access to student records.  

### 7. **Modern User Interface**  
- Responsive, user-friendly design using Bootstrap.  
- Enhanced UI elements such as cards and form widgets.  

### 8. **Social Authentication**  
- Google sign-in integration for secure and quick access.  
- Safe API key management for enhanced security.  

---

## 📄 Conclusion  

The **College Bus Management System** provides a comprehensive, scalable, and secure platform for managing college transportation. By leveraging Django’s robust backend capabilities and Bootstrap’s modern design components, this project ensures efficient management while offering a user-friendly interface.  

---  

