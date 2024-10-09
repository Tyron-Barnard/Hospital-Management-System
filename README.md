# Hospital Management System

The **Hospital Management System** is a web-based platform developed using Django to efficiently manage hospital operations, including managing doctors, patients, appointments, and administrative tasks. This system aims to streamline the workflow for hospital staff and improve patient care.

## Features
- **Admin Panel**: Manage doctors, patients, and appointments.
- **Doctor Module**: Allows doctors to manage their schedules and patient records.
- **Patient Module**: Patients can book appointments and view their medical history.

## How to Run the Project
1. Download or clone the repository:  
   `git clone https://github.com/Tyron-Barnard/Hospital-Management-System.git`

2. Navigate to the project directory:  
   `cd Hospital-Management-System`

3. Install the required dependencies:  
   `pip install -r requirements.txt`

4. Run database migrations:  
   `python manage.py migrate`

5. Start the Django development server:  
   `python manage.py runserver`

6. Visit the URL [http://127.0.0.1:8000](http://127.0.0.1:8000) in your browser to access the application.

## Login Details
### **Admin**
- **Username**: `admin@gmail.com`
- **Password**: `Test@123`

### **Doctor**
- **Username**: `john12@gmail.com`
- **Password**: `Test@123`  
- _OR register a new doctor._

### **User/Patient**
- **Username**: `amit123@gmail.com`
- **Password**: `Test@123`  
- _OR register a new user/patient._

## Project Structure
- `hospital/`: Contains settings, URLs, and configurations for the Django app.
- `doctors/`: Manages doctor-related functionality.
- `patients/`: Handles patient profiles and appointments.
- `templates/`: Contains HTML templates for rendering the user interface.
- `static/`: Contains static files like CSS and JavaScript.

## Technologies Used
- **Backend**: Django (Python)
- **Database**: SQLite (or another configured DB)
- **Frontend**: HTML, CSS, JavaScript

## How to Set Up the Database
1. Open **PHPMyAdmin** or your preferred DBMS.
2. Create a database with the name `hospitaldb`.
3. Run migrations:  
   `python manage.py migrate`

4. Populate the database using fixtures or through the admin panel.

## License
This project is licensed under the MIT License.
