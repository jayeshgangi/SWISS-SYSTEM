# Swiss-System Tournament Manager ♟️

A web-based application to manage chess tournaments using the **Swiss System pairing method**.
This tool helps organizers create tournaments, generate pairings automatically, track results, and calculate tie-breakers.

## 🚀 Features

* Create and manage chess tournaments
* Automatic Swiss-system round pairings
* Player registration and management
* Match result entry
* Tie-break calculations
* Tournament standings dashboard
* Round-wise match view

## 🛠 Tech Stack

* **Backend:** Python (Flask)
* **Frontend:** HTML, CSS, JavaScript
* **Database:** SQLite
* **Templates:** Jinja2

## 📂 Project Structure

```
Swiss-System/
│
├── app.py
├── db/
├── templates/
│   ├── dashboard.html
│   ├── rounds.html
│   └── setuptournament.html
│
├── static/
└── README.md
```

## ⚙️ Installation

1. Clone the repository

```
git clone https://github.com/jayeshgangi/Swiss-System.git
```

2. Navigate to the project folder

```
cd Swiss-System
```

3. Create virtual environment

```
python -m venv venv
```

4. Activate virtual environment

Windows:

```
venv\Scripts\activate
```

Mac/Linux:

```
source venv/bin/activate
```

5. Install dependencies

```
pip install -r requirements.txt
```

6. Run the application

```
python app.py
```

## 📊 How It Works

1. Create a tournament
2. Add players
3. Generate pairings for each round
4. Enter match results
5. View updated standings with tie-breakers

## 📌 Future Improvements

* FIDE compliant tie-break rules
* Player rating integration
* Export results (PDF / Excel)
* Online multiplayer support
* Improved UI/UX

## 👨‍💻 Author

**Jayesh Gangi**

---

⭐ If you found this project useful, consider giving it a star!
