# Akshat Kothari – Tableau Reference Website

A Flask-based reference website that brings together Tableau Dashboard and Tableau Story visualizations created by **Akshat Kothari** in one place.

The website provides an accessible way to explore the visualizations through embedded Tableau Public content.

## 🌐 Live Website

**[Visit the Live Website](https://akshat-kothari-tableau-reference.onrender.com/)**

## 📊 Tableau Visualizations

Explore the original Tableau visualizations:

- **Tableau Dashboard:** [View Dashboard](https://public.tableau.com/views/Dashboard1_17936379054230/Dashboard1)
- **Tableau Story:** [View Story](https://public.tableau.com/shared/3TYCX9NSN)

## ✨ Features

- Embedded Tableau Dashboard.
- Embedded Tableau Story.
- Simple and user-friendly interface.
- Responsive website layout.
- Centralized access to Tableau visualizations.
- Hosted online using Render.

## 🛠️ Technologies Used

- **Python** – Backend programming.
- **Flask** – Web application framework.
- **HTML** – Website structure.
- **CSS** – Website styling.
- **Tableau Public** – Data visualization and interactive dashboards.
- **Git & GitHub** – Version control and source code hosting.
- **Render** – Website deployment and hosting.

## 📁 Project Structure

```text
Akshat_Kothari_Tableau_Reference/
│
├── app.py
├── templates/
│   └── index.html
│
├── static/
│   └── style.css
│
├── requirements.txt
├── Procfile
├── README.md
└── .gitignore
```

## ⚙️ Run Locally

Follow these steps to run the project on your computer.

### 1. Clone the repository

```bash
git clone https://github.com/Akshatkothari25/Akshat-Kothari-Tableau-Reference.git
```

### 2. Navigate to the project folder

```bash
cd Akshat-Kothari-Tableau-Reference
```

### 3. Create a virtual environment

```bash
python3 -m venv venv
```

### 4. Activate the virtual environment

For macOS/Linux:

```bash
source venv/bin/activate
```

### 5. Install dependencies

```bash
pip install -r requirements.txt
```

### 6. Run the application

```bash
python app.py
```

### 7. Open in your browser

```text
http://127.0.0.1:5000
```

## 🚀 Deployment

The application is deployed using **Render**.

Deployment configuration:

| Setting | Value |
|---|---|
| Runtime | Python 3 |
| Build Command | `pip install -r requirements.txt` |
| Start Command | `gunicorn app:app` |
| Hosting Platform | Render |

## 👨‍💻 Credits & Attribution

**Original Tableau Visualizations:** Akshat Kothari

This website is a separate reference showcase created to provide convenient access to the original Tableau Dashboard and Story.

All original Tableau visualizations and their underlying work belong to their respective creator. This project does not claim authorship of those visualizations.

## 📄 License

This repository is intended as a reference website. The original Tableau visualizations remain the property of their respective creator. Please obtain permission before redistributing or reusing their work.

---

**Built with Python, Flask, HTML, CSS and Tableau Public.**
