# 🩺 Disease Tracker Web Application

A web-based application that allows users to track diseases, symptoms, medications, diets, and precautions. This tool is designed to assist users in monitoring their health conditions and staying informed with personalized health data.

---

## 🔍 Features

- 🧾 **Symptom Tracking** – Log and monitor symptoms over time.
- 💊 **Medication Management** – View medications related to diseases.
- 🥗 **Diet Suggestions** – Recommended diets for different conditions.
- ⚠️ **Precautions List** – Safety tips and health advice for each disease.
- 📄 **Informational Pages** – Includes About, Contact, Blog, Developer Info, etc.

---

## 🗂️ Project Structure

| File/Folder        | Description |
|--------------------|-------------|
| `index.html`       | Main landing page of the website. |
| `about.html`       | About the application. |
| `blog.html`        | Blog section for updates or articles. |
| `contact.html`     | Contact form or information page. |
| `developer.html`   | Info about the developer or development team. |
| `description.csv`  | Descriptions of diseases. |
| `diets.csv`        | Diet recommendations for each condition. |
| `medications.csv`  | Medication data for diseases. |
| `precautions_df.csv` | Preventive measures for various conditions. |
| `symtoms_df.csv`   | Symptom data *(note: consider renaming to `symptoms_df.csv`)*. |
| `symptomtracker.py` | Backend script for tracking symptoms and possibly making predictions. |
| `svc.pkl`          | Serialized ML model (SVC - Support Vector Classifier). |
| `pyvenv.cfg`       | Python virtual environment configuration. |

---

## 🚀 Getting Started

### Prerequisites

Ensure Python is installed. Then install the necessary packages:

```bash
pip install pandas flask scikit-learn
````

### Running the Application

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/your-username/disease-tracker.git
   cd disease-tracker
   ```

2. **(Optional) Create and Activate Virtual Environment:**

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Run the Backend (Flask App or Script):**

   ```bash
   python symptomtracker.py
   ```

4. **Open `index.html` in your browser** or host it using a simple HTTP server:

   ```bash
   python -m http.server
   ```

---

## 🧠 Machine Learning Model

* The file `svc.pkl` contains a pre-trained **Support Vector Classifier** model.
* It's used in the backend script (`symptomtracker.py`) to make predictions based on user-input symptoms.
* Input data is likely processed from `symtoms_df.csv`.

---

## 📊 Data Sources

All data used by the app is stored in CSV format:

* `description.csv` – Basic disease descriptions.
* `diets.csv` – Diet plans per disease.
* `medications.csv` – Recommended or prescribed medications.
* `precautions_df.csv` – Safety measures and health precautions.
* `symtoms_df.csv` – Common symptoms for each disease.

---

## 🛠️ Future Improvements

* ✅ Rename `symtoms_df.csv` to `symptoms_df.csv` for clarity.
* 🔐 Add user authentication and profiles.
* 📈 Add data visualization (charts for symptom trends).
* 🌐 API integration for real-time health updates.
* 📲 Mobile-responsive design.

---

## 👨‍💻 Developer

For more information, please visit the `developer.html` page or reach out via the `contact.html` form.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

