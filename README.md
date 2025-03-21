# Bethel Church Web Application

A modern, Flask-based web application designed to serve the needs of Bethel church community. This application aims to streamline church operations and enhance community engagement through technology.

## Features (Planned)

- 📅 Event Calendar & Service Schedule
- 🙏 Prayer Request Management
- 📢 Announcements & News Updates
- 💰 Online Giving/Donations
- 📝 Sermon Notes & Archives
- 👥 Member Directory
- 📱 Mobile-Responsive Design

## Technology Stack

- **Backend**: Python Flask
- **Database**: SQLite (development) / PostgreSQL (production)
- **Frontend**: HTML5, CSS3, JavaScript
- **CSS Framework**: Bootstrap 5
- **Authentication**: Flask-Login
- **Forms**: Flask-WTF
- **Database ORM**: SQLAlchemy

## Getting Started

### Prerequisites

- Python 3.8 or higher
- pip (Python package manager)
- Virtual environment (recommended)

### Installation

1. Clone the repository
```bash
git clone https://github.com/charpatae/Bethel.git
cd Bethel
```

2. Create and activate virtual environment
```bash
python -m venv venv
# On Windows
venv\Scripts\activate
# On macOS/Linux
source venv/bin/activate
```

3. Install dependencies
```bash
pip install -r requirements.txt
```

4. Set up environment variables
```bash
# Create .env file and add:
FLASK_APP=app
FLASK_ENV=development
SECRET_KEY=your-secret-key
```

5. Initialize the database
```bash
flask db init
flask db migrate
flask db upgrade
```

6. Run the application
```bash
flask run
```

The application will be available at `http://localhost:5000`

## Project Structure

```
Bethel/
├── app/
│   ├── __init__.py
│   ├── models/
│   ├── routes/
│   ├── templates/
│   └── static/
├── migrations/
├── tests/
├── config.py
├── requirements.txt
└── run.py
```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contact

Project Link: [https://github.com/charpatae/Bethel](https://github.com/charpatae/Bethel)

---

Made with ❤️ for Bethel Church