# 💪 Ideal Body Tracker

The **Ideal Body Tracker** is a web application that helps users monitor their health by calculating BMI (Body Mass Index) and collecting personal health data like age, gender, sleep, water intake, and more.


## 🛠 Tech Stack

- **Frontend:** HTML, CSS, JavaScript  
- **Backend:** Python (Flask)  
- **Hosting:** Localhost / Flask Server  

## 🚀 Features

- Collects user details like:
  - Full Name
  - Age
  - Gender
  - Diet Type
  - Water Intake
  - Sleep Duration
  - Weight
  - Height
- Calculates **BMI** using the inputted data.
- Clean and responsive UI.


## 🧠 How BMI is Calculated

The BMI is calculated using the formula:

```python
BMI = weight_kg / (height_m ** 2)
```

> In your project, if height is taken in centimeters, make sure to convert it to meters before calculating BMI.

## 🧪 How to Run

1. Clone this repository:

```bash
git clone https://github.com/your-username/ideal-body-tracker.git
cd ideal-body-tracker
```

2. Create a virtual environment and activate it:

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

4. Run the Flask application:

```bash
python app.py
```

5. Open your browser and go to `http://127.0.0.1:5000/`

## 📁 Folder Structure

```
ideal-body-tracker/
│
├── static/                # CSS & JS files
├── templates/             # HTML files (home.html, result.html)
├── app.py                 # Main Flask app
└── README.md              # Project description
```

## ✅ To-Do

- [ ] Add input validation
- [ ] Store user history in a database
- [ ] Suggest ideal water/sleep intake based on BMI

