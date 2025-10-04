# HealthData IQ – Hospital Insights & Patient Analytics

## Overview

HealthData IQ is an analytics project focused on uncovering meaningful patterns and actionable insights from hospital performance and patient feedback across the United States. Using official CMS hospital data, we help stakeholders understand healthcare quality, patient satisfaction, mortality rates, and accessibility.

---

## Dataset

- **Source:** [CMS Hospital General Information (Kaggle)](https://www.kaggle.com/datasets/CMS/hospital-general-information)
- **Features:**
  - Hospital Name, Type, Ownership, Location (City, State, County)
  - Ratings (Overall, Safety, Mortality, Readmission)
  - Emergency Services Availability
  - Patient Survey Results

---

## Team & Division of Work

| Name    | Tasks                                                                 |
|---------|-----------------------------------------------------------------------|
| Shubham | Data Cleaning: handle missing values, format/rename columns, fix text inconsistencies |
| Akash   | Exploratory Data Analysis (EDA): perform descriptive statistics, analyze trends, generate metrics |
| Sumit   | Visualization & Insights: create all graphs and charts, summarize key findings, write interpretations |

*Note: Optional tasks such as SQL analysis, advanced statistics, and dashboard creation were **not** included in this project.*

---

## Project Structure

```bash
├── data/
│   └── hospital_cleaned.csv      # Cleaned dataset
├── notebooks/
│   └── hospital_analysis.ipynb   # Main Jupyter notebook
├── visuals/
│   └── *.png / *.jpg             # Exported visualizations
├── README.md
```

---

## How to Run

1. **Clone the repository:**
   ```bash
   git clone https://github.com/<your-org>/<your-repo>.git
   cd <your-repo>
   ```

2. **Install dependencies:**
   - Recommended: Create a virtual environment
   - Install required packages:
     ```bash
     pip install pandas numpy matplotlib seaborn plotly
     ```

3. **Open the Jupyter notebook:**
   ```bash
   jupyter notebook notebooks/hospital_analysis.ipynb
   ```

---

## Key Analysis Questions

- How does the distribution of hospital types (general acute care, specialty, critical access) vary across states, and which types are associated with higher patient satisfaction?
- What is the relationship between emergency service availability and average hospital ratings at the state level?
- Which states consistently rank highest and lowest in hospital performance, and what factors contribute to these disparities?
- How do patient satisfaction scores compare between specialty hospitals and general acute care hospitals?
- What trends are observed in hospital ownership (private, nonprofit, government), and how do these ownership categories impact hospital ratings?
- Is there significant variation in hospital ratings within the same hospital type, and what operational or locational factors might explain this spread?

---

## Methods & Tools

- **Data Cleaning:** Pandas, NumPy
- **Visualization:** Matplotlib, Seaborn, Plotly

---

## Deliverables

- **Cleaned Dataset:** `data/hospital_cleaned.csv`
- **Jupyter Notebook:** `notebooks/hospital_analysis.ipynb`
- **Visualizations & Insights:**  
  All key insights, graphs, and suggestions are available in the interactive dashboard:
  - [Hospital Performance Dashboard](https://hospitalinfoiq.netlify.app/)
- **Presentation Video:** [Link to Video](#) *(YouTube/Drive)*

---

## Results & Insights

All core findings, data visualizations, and actionable suggestions can be explored interactively in the [Hospital Performance Dashboard](https://hospitalinfoiq.netlify.app/).

---

## References

- [CMS Hospital Data on Kaggle](https://www.kaggle.com/datasets/CMS/hospital-general-information)
- [Hospital Performance Dashboard](https://hospitalinfoiq.netlify.app/)

---

## License

This project is for educational purposes only. Please refer to the dataset's original license for usage restrictions.
