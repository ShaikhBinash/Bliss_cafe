# Bliss Cafe

## Overview
Bliss Cafe is a beautifully designed web application built using Django, providing an elegant and seamless experience for customers looking to explore the cafe's menu, place orders, and get updates on special offers.

## Features
- Browse the cafe's menu.
- Place online orders.

## Technical Details
- **Framework:** Django
- **Frontend:** HTML, CSS, JavaScript, Bootstrap
- **Database:** SQLite / PostgreSQL / MySQL
- **Authentication:** Django’s built-in authentication system

## Admin Login Credentials
- **Username:** binashshaikh
- **Email:** binashshaikh972@gmail.com
- **Password:** Cafe_Website

## Setup Instructions

### Prerequisites
- Python 3.x
- Django
- PostgreSQL / SQLite / MySQL (as per configuration)

### Steps to Run the Project
1. **Clone the Repository**
   ```sh
   git clone <repository-url>
   cd bliss-cafe
   ```
2. **Create a Virtual Environment & Activate It**
   ```sh
   python -m venv venv
   source venv/bin/activate  # Mac/Linux
   venv\Scripts\activate  # Windows
   ```
3. **Install Dependencies**
   ```sh
   pip install -r requirements.txt
   ```
4. **Apply Migrations**
   ```sh
   python manage.py migrate
   ```
5. **Create a Superuser (if needed)**
   ```sh
   python manage.py createsuperuser
   ```
6. **Run the Development Server**
   ```sh
   python manage.py runserver
   ```
7. **Access the Application**
   - Website: [http://127.0.0.1:8000](http://127.0.0.1:8000)
   - Admin Panel: [http://127.0.0.1:8000/admin](http://127.0.0.1:8000/admin)

## Contributing
Feel free to contribute by submitting pull requests or reporting issues.

## License
This project is open-source and available under the MIT License.

## Contact
For any queries or suggestions, reach out via email: **binashshaikh972@gmail.com**.

