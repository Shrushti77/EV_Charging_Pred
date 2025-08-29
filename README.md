# ⚡ EV Adoption Forecasting

This project predicts **electric vehicle (EV) adoption trends** using historical data and machine learning. It provides **multi-year forecasts** of EV growth across counties/regions and lets you compare adoption patterns between areas.

Built as part of a virtual internship on *Artificial Intelligence & Data Analytics with Green Skills* under the **AICTE – Skills4Future program**, in collaboration with **Shell India & Edunet Foundation**. 🌱🚗

---

## 📌 Project Overview
- **Objective** → Forecast EV adoption and analyze trends at a regional level  
- **Approach** → Apply ML on EV population datasets to predict future growth  
- **Key Features**
  - Forecast EV adoption for a selected region
  - Compare up to 3 regions side by side
  - Visualize **historical vs predicted** trends
  - Interactive Streamlit dashboard

---

## 🛠️ Tech Stack
- Python, Pandas, NumPy
- Scikit-learn (modeling)
- Plotly / Matplotlib (visualization)
- Streamlit (web app)
- Joblib / Pickle (model serialization)

---

**Note:** The app is flexible — on first run it asks you to map which columns are *Year*, *Region* and *EV Count*, so it works with different CSV schemas.

---

## 🚀 Getting Started
### 1) Clone and enter the repo
```bash
git clone https://github.com/your-username/ev-adoption-forecasting.git
cd ev-adoption-forecasting
```
---

### 2) Create a virtual environment (recommended)

```
python -m venv .venv
# Windows
.venv\Scripts\activate
# macOS/Linux
source .venv/bin/activate
```
---
### 3) Install dependencies
```
pip install -r requirements.txt
```
---
### 4) Place data/model files (if not already present)

- preprocessed_ev_data.csv
- forecasting_ev_model.pkl (optional)
---

### 5) Run the app
```
streamlit run app.py
```
---

## 📈 Screenshots (optional)

<img width="1280" height="691" alt="image" src="https://github.com/user-attachments/assets/d479172f-8f13-4021-80e5-5ce1f546652b" />

- Single region forecast view
- Multi-region comparison

## 🙏 Acknowledgments

Developed as part of the AICTE – Skills4Future program, supported by Shell India & Edunet Foundation.
