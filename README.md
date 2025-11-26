# 📊 Global Terrorism Database (GTD) – Dataset Overview

This repository contains the **Global Terrorism Database (GTD)** dataset (`globalterrorismdb_0718dist.csv`), a comprehensive open-source database that documents terrorist events worldwide from **1970 to 2017**.

---

## 📖 About the Dataset

The Global Terrorism Database is one of the largest publicly available databases on terrorist incidents, containing detailed information on **180,000+ events**.  
Each record includes information about:

- Date and location of the attack  
- Perpetrator group(s)  
- Attack type and target  
- Weapons used  
- Casualties (killed and wounded)  
- Motive (when available)

This dataset is commonly used in **data analytics, machine learning, visualization, academic research, and security studies**.

---

## 📂 File Information

- **File name:** `globalterrorismdb_0718dist.csv`
- **Data Sources:** `https://www.kaggle.com/datasets/START-UMD/gtd`
- **Encoding:** `Latin-1 (ISO-8859-1)`  
- **Number of rows:** ~181,000  
- **Number of columns:** 135  

---

## 📑 Key Columns

| Column | Description |
|--------|-------------|
| `eventid` | Unique ID for each incident |
| `iyear`, `imonth`, `iday` | Date of the event |
| `country`, `country_txt` | Country code and name |
| `region`, `region_txt` | Region code and name |
| `city` | City where the incident took place |
| `attacktype1`, `attacktype1_txt` | Primary attack type |
| `targtype1`, `targtype1_txt` | Target type |
| `gname` | Perpetrator group name |
| `weaptype1`, `weaptype1_txt` | Weapon used |
| `nkill`, `nwound` | Fatalities and injuries |
| `summary` | Short description of the incident |
| `motive` | Possible motive |

---

