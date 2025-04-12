# State-Infrastructure-Progress-Report
# 🛣️ Road Construction Analysis - PMGSY Projects

This project presents a comprehensive analysis of road construction projects under the **Pradhan Mantri Gram Sadak Yojana (PMGSY)**. The objective is to examine the **distribution**, **completion**, and **length** of road work sanctioned and completed across various Indian states.

---

## 📌 Objectives

- ✅ Analyze **average road length sanctioned per project and per state**
- ✅ Calculate **road completion rate (%) per state**
- ✅ Identify **states with the highest number of sanctioned projects**
- ✅ Visualize data using **Pivot Tables** and **Charts**
- ✅ Provide **insights** to track PMGSY implementation progress

---

## 📂 Dataset Overview

File: `roadconstruction.csv`

**Key Columns:**
- `STATE_NAME`: Name of the state
- `LENGTH_OF_ROAD_WORK_SANCTIONED_KM`: Sanctioned length of road (km)
- `LENGTH_OF_ROAD_WORK_COMPLETED_KM`: Completed length of road (km)
- `PROJECT_ID` or `UNIQUE_ID`: Each road project’s identifier (if available)
- `road_completion_`: Flag (1 = completed, 0 = not completed)

---

## 📈 Pivot Table Logic

### 1️⃣ **Average Road Length per Project**
**Formula:**
**Pivot Setup:**
- **Rows**: `STATE_NAME`
- **Values**: `LENGTH_OF_ROAD_WORK_SANCTIONED_KM` → Set to **Average**

---

### 2️⃣ **Road Completion Rate (%) per State**
**Formula:**
**Pivot Setup:**
- **Rows**: `STATE_NAME`
- **Values**:
  - `LENGTH_OF_ROAD_WORK_SANCTIONED_KM` → Sum
  - `LENGTH_OF_ROAD_WORK_COMPLETED_KM` → Sum
- Add Calculated Field:

---

## 📊 Sample Visuals

- 🔘 **Donut Chart**: Proportion of sanctioned projects by state
- 📏 **Bar Chart**: Completion rate across states
- 📐 **Table View**: Average road length per project



---

## 🛠️ Tools Used

- **Microsoft Excel** – Pivot Tables, Charts, and Calculated Fields

- **GitHub** – Project versioning and sharing

---

## 💡 How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/pmgsy-road-analysis.git
