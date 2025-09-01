# Forest Fires ML Project

This project is a **Flask web application** that predicts the burned area of forest fires using a trained **Ridge Regression model**. The app provides a simple web interface where users can input environmental parameters and get instant predictions.

---

## 🚀 Features
- Flask-based web application
- Pre-trained Ridge Regression model for prediction
- StandardScaler applied to input features before prediction
- User-friendly HTML templates (`index.html` and `home.html`)
- Modular structure with `models/` folder for pickled ML artifacts

---

## 📂 Project Structure
```

├── app.py                # Flask application entry point
├── models/               # Pickled ML models
│   ├── ridge.pkl         # Ridge Regression model
│   └── scaler.pkl        # StandardScaler object
├── templates/            # HTML templates for Flask
│   ├── index.html        # Landing page with input form
│   └── home.html         # Results page with prediction output
├── requirements.txt      # Python dependencies
└── README.md             # Project documentation

````

---

## ⚙️ Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/forest-fire-prediction.git
   cd forest-fire-prediction
````

2. **Create and activate a virtual environment**

   ```bash
   python -m venv venv
   source venv/bin/activate   # On Linux/Mac
   venv\Scripts\activate      # On Windows
   ```

3. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Flask app**

   ```bash
   python app.py
   ```

5. **Access the app**
   Open your browser at:
   👉 `http://127.0.0.1:5000/`

---

## 🧪 Usage

1. Go to the homepage (`/`)
2. Enter input values:

   * Temperature
   * RH (Relative Humidity)
   * Ws (Wind speed)
   * Rain
   * FFMC (Fine Fuel Moisture Code)
   * DMC (Duff Moisture Code)
   * ISI (Initial Spread Index)
   * Classes (Fire severity class)
   * Region (Geographic region)
3. Click **Predict**
4. The predicted burned area will be displayed on the results page.

---

## 📦 Dependencies

* Flask
* Scikit-learn
* Pandas
* NumPy

Install them using:

```bash
pip install -r requirements.txt
```

---

## 📸 Screenshots

### Input Page

![Index Page](./screenshots/index.png)

### Prediction Result

![Home Page](./screenshots/home.png)

---

## 📌 Notes

* Make sure `models/ridge.pkl` and `models/scaler.pkl` exist in the `models/` folder before running.
* The app can be deployed to platforms like **Heroku**, **Render**, or **AWS EC2**.

---

## 📝 License

This project is licensed under the MIT License.
Feel free to use, modify, and distribute.

---

```

⚡ I kept it **internship/portfolio ready** — clear structure, setup steps, screenshots section (you can drop your PNGs in a `/screenshots/` folder), and deployment note.  

Do you also want me to generate a **requirements.txt** file from your `app.py` automatically?
```

