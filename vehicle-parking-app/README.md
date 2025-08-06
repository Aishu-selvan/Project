# 🚗 Vehicle Parking App

A full-featured web application to manage vehicle parking using a simple and intuitive interface. This app enables users to search and reserve parking spots and allows administrators to manage lots, view reservations, and analyze usage statistics.

---

## 🔧 Features

### 👥 Admin
- Secure login authentication
- Add, update, or delete parking lots and spots
- View all user reservations
- Track real-time availability
- Visual dashboards and charts using Chart.js

### 🚗 User
- Search available parking spots
- Book/reserve a parking space
- View reservation confirmation and cost
- Cancel existing reservation

---

## 📽️ Demo Video

🎥 [Click here to watch the demo](https://drive.google.com/file/d/1I3FSS2PoEp8ktXUtnm0XcSY3vk05cRST/view)

This video walkthrough demonstrates the features and usage of the Vehicle Parking App.

---

## 🛠️ Tech Stack

- **Backend**: Python, Flask
- **Frontend**: HTML, CSS, Bootstrap, Jinja2
- **Database**: SQLite
- **Visualization**: Chart.js

---

### 1. Clone the Repository

```bash
git clone https://github.com/Aishu-selvan/Project.git
cd Project/vehicle-parking-app
2. Create a Virtual Environment (optional but recommended)
python -m venv venv
source venv/bin/activate     # Windows: venv\Scripts\activate
3. Install Requirements
pip install -r requirements.txt
4. Run the Application
python app.py
Then open http://127.0.0.1:5000 in your web browser.
📁 Project Structure

vehicle-parking-app/
├── app.py                      # Main Flask application
├── models.py                   # Database models
├── controllers/
│   └── admin.py                # Admin-specific routes and logic
├── templates/
│   ├── base.html
│   ├── login.html
│   ├── dashboard.html
│   └── reserve.html
├── static/
│   ├── css/
│   ├── js/
├── parking_app.db              # SQLite database file
├── requirements.txt
└── README.md

🔐 Admin Credentials (for testing only)

Username: admin
Password: admin123

⚠️ Please change the default credentials before deploying this app in production.

📝 License
This project is licensed under the MIT License.









