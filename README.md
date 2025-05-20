# 🛠️ Smart Shaker Intelligence Suite

A Streamlit-based dashboard for real-time monitoring of shaker screen performance, drilling parameters, and mud quality — designed for mud engineers, rig supervisors, and field operations teams.

---

## 🔍 Key Features

| Module                     | Description                                                                 |
|----------------------------|-----------------------------------------------------------------------------|
| 📌 Summary & KPIs          | Aggregates avg GPM, screen utilization, ROP, shaker load, bit depth delta  |
| 🔍 Mud Performance         | Flags daily alerts, shows Mud Quality Index & flow warnings                |
| 📈 Utilization Trends      | Real-time plots for GPM, ROP, solids, and screen load over time             |
| 📉 G-Force Monitor         | Detects possible mechanical faults via shaker unit response drop           |
| 📊 KPI Matrix              | Color-coded health snapshot across critical indicators                     |
| 📤 Export Reports          | One-click Excel download of all parsed and calculated values               |

---

## 🚀 How to Run

### Option 1: Run Locally

```bash
# 1. Clone the repo
git clone https://github.com/your-org/shaker-dashboard.git
cd shaker-dashboard

# 2. Install dependencies
pip install -r requirements.txt

# 3. Launch the app
streamlit run app.py
