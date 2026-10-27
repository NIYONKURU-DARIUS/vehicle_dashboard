# 🚗 Vehicle Machine Learning Dashboard

[![Django](https://img.shields.io/badge/Django-5.0+-green.svg)](https://www.djangoproject.com/)
[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-2.0+-darkblue.svg)](https://pandas.pydata.org/)
[![Plotly](https://img.shields.io/badge/Plotly-5.0+-purple.svg)](https://plotly.com/)
[![GitHub Repo](https://img.shields.io/badge/GitHub-vehicle__dashboard-black.svg)](https://github.com/NIYONKURU-DARIUS/vehicle_dashboard)

A Django-based web dashboard designed for exploring and analyzing vehicle datasets for Machine Learning workflows. It provides summary statistics, one-way frequency distribution tables, and an interactive Bootstrap 5 interface built for vehicle market insights and feature analysis.

---

## 🌟 Features

- **📊 Dataset Integration**: Seamlessly loads and parses large vehicle machine learning datasets (`vehicles_ml_dataset.csv`) using Pandas.
- **📋 Frequency Distribution Tables**: Computes one-way manufacturer frequency distributions rendered into responsive, striped Bootstrap data tables.
- **🎨 Modern Responsive UI**:
  - Sticky sidebar navigation with smooth Bootstrap Scrollspy.
  - Clean card-based modular layout for future ML model outputs, metrics, and visual plots.
- **⚡ Interactive Analytics Ready**: Pre-configured with Plotly and Pandas for extending into correlation matrices, price distributions, and predictive modeling.

---

## 📂 Project Structure

```text
vehicle_ml_dashboard/
├── config/                     # Project configuration
│   ├── __init__.py
│   ├── asgi.py
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
├── dummy_data/
│   └── vehicles_ml_dataset.csv # Vehicle dataset
├── vehicles/                   # Vehicles application
│   ├── dashboard.py            # Pandas analytical functions & table generators
│   ├── views.py                # Dashboard request views
│   ├── urls.py                 # URL routing
│   ├── models.py
│   └── templates/vehicles/
│       └── index.html          # Responsive Bootstrap dashboard UI
├── manage.py
├── requirements.txt            # Python dependencies
├── .gitignore
└── README.md
```

---

## 🛠️ Installation & Setup

### 1. Clone the Repository
```bash
git clone https://github.com/NIYONKURU-DARIUS/vehicle_dashboard.git
cd vehicle_dashboard
```

### 2. Set Up Virtual Environment
```bash
# Windows
python -m venv venv
.\venv\Scripts\activate

# Linux / macOS
python3 -m venv venv
source venv/bin/activate
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

### 4. Apply Database Migrations
```bash
python manage.py makemigrations
python manage.py migrate
```

### 5. Launch the Dashboard
```bash
python manage.py runserver
```

Open your browser and navigate to:
[http://127.0.0.1:8000/](http://127.0.0.1:8000/)

---

## 📦 Dependencies

- **Django**: High-level Python web framework.
- **Pandas**: Fast and flexible data analysis library.
- **Plotly**: Interactive visualization library for Python.
- **Bootstrap 5**: Modern frontend styling and responsive UI components.

---

## 👤 Author

- **Darius NIYONKURU**
- GitHub: [@NIYONKURU-DARIUS](https://github.com/NIYONKURU-DARIUS)
- Email: [dariusniyonkuru351@gmail.com](mailto:dariusniyonkuru351@gmail.com)

---

## 📄 License

This project is licensed under the MIT License.
