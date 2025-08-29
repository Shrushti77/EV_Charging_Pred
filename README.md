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

## 📈 Screenshots 
<img width="1919" height="1006" alt="Screenshot 2025-08-25 071056" src="https://github.com/user-attachments/assets/ae145533-cfaf-4e89-a652-fe47b636f826" />

## Single region forecast view
<img width="1919" height="389" alt="Screenshot 2025-08-25 071807" src="https://github.com/user-attachments/assets/1b81779f-0a27-4526-9371-05d875a17119" />
<img width="1899" height="1079" alt="Screenshot 2025-08-25 072022" src="https://github.com/user-attachments/assets/91328fe8-8581-4ee7-b1a9-456b4d466592" />

## Multi-region comparison view
<img width="1919" height="509" alt="Screenshot 2025-08-25 072152" src="https://github.com/user-attachments/assets/a1942895-91e3-454a-8efd-5261b25342e1" />
<img width="1919" height="1079" alt="Screenshot 2025-08-25 072246" src="https://github.com/user-attachments/assets/41c621ce-4527-43b1-a0a3-184d91bb0bd7" />



