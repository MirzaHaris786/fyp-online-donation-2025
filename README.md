# fyp-online-donation-2025
A web-based platform developed as a Final Year Project (FYP) to facilitate online donations for various causes. The system allows donors to contribute to campaigns securely and enables admins to manage donation records, campaigns, and users effectively.

🔍 Features

- 💳 Secure donor registration and login
- 📦 Campaign creation and management
- 💰 Donation processing (dummy payment simulation)
- 📊 Admin dashboard to manage users and donations
- 📄 Donation history for donors
- 📱 Responsive user interface using HTML, CSS, and Bootstrap

## 🛠️ Technologies Used

- **Backend**: Python, Django
- **Frontend**: HTML, CSS, Bootstrap, JavaScript
- **Database**: PostgreSQL / SQLite
- **Version Control**: Git, GitHub

## 🚀 How to Run Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/online-donation-system.git

   cd online-donation-system
   python -m venv venv
   source venv/bin/activate   # or venv\Scripts\activate on Windows
    
   pip install -r requirements.txt

   python manage.py migrate
   python manage.py runserver

