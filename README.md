# Seed Forecast BI Project

This Business Intelligence project analyzes virus seed inventory alongside planned production campaigns to support seed manufacturing decisions. The objective is to anticipate shortages, optimize production timing, and inform inventory planning.

---

## 📊 Project Goals

- Identify forecasted seed usage by campaign date
- Compare current inventory to expected usage per seed lot
- Highlight potential shortages and overages
- Recommend manufacturing actions based on demand trends

---

## 📁 Project Structure

```text
seed-forecast-bi-project/
├── data/                   # Source Excel and CSV files
├── notebooks/              # Jupyter Notebooks for analysis
├── images/                 # Visualizations for reports
├── requirements.txt        # Python dependencies
├── .gitignore              # Ignored files and folders
└── README.md               # Project documentation

---

## 📂 Data Sources

- `25seed_sched.xlsx` — Production campaign schedule with required seed lots and theoretical amps
- `seed_inv24apr.xlsx` — Inventory snapshot of available seed lots
- `seed_demand_inventory_full_inventory.csv` — Merged dataset used for reporting and visualization

---

## 💻 How to Run the Project

1. Clone this repository:
   ```bash
   git clone https://github.com/asbestositgets/seed-forecast-bi-project.git
   cd seed-forecast-bi-project
