# COVID-19 Global Data Tracker

## Introduction

The COVID-19 pandemic has significantly impacted countries worldwide, prompting urgent responses in healthcare, policy, and vaccination. In this data analysis project, we examine global trends in COVID-19 cases, deaths, and vaccinations using real-world data from [Our World in Data](https://ourworldindata.org/covid-data).

The primary objective is to explore how the pandemic evolved over time in selected countries — **Kenya**, **United States**, and **India** — and to gain insights into their responses and outcomes.

### Project Objectives
- Import and clean COVID-19 global data.
- Analyze trends in cases, deaths, and vaccinations over time.
- Compare metrics across countries.
- Visualize trends using graphs and charts.
- Summarize findings with data-driven insights.

## Conclusion & Key Insights

After analyzing COVID-19 data for Kenya, the United States, and India, we derived the following insights:

### 📌 Insight 1: The United States had the highest total vaccination count.
The US started early and ramped up quickly, surpassing both Kenya and India in terms of total and per capita vaccinations.

### 📌 Insight 2: India faced the most significant spike in daily new cases in mid-2021.
This period coincides with the spread of the Delta variant, leading to a huge surge in infections and fatalities.

### 📌 Insight 3: Kenya’s vaccination progress was slower but gradually improved.
Although Kenya began vaccinations later, consistent efforts have led to increased coverage over time.

### 📌 Insight 4: Death rates remained relatively low in Kenya compared to India and the US.
This might be influenced by demographic factors such as a younger population or underreporting.

---

## Final Thoughts

This analysis highlights the importance of timely vaccination, real-time data collection, and regional-specific responses during global health crises. Data science tools such as Python, pandas, matplotlib, and seaborn provide valuable insights that can guide decision-making and improve public health outcomes.

A data analysis project using real-world COVID-19 data to explore global trends in cases, deaths, and vaccinations across different countries. The project is implemented in a Jupyter Notebook and includes data cleaning, exploratory analysis, visualizations, and narrative insights.

---

## 🛠️ Tools & Libraries Used

- Python 3
- Jupyter Notebook
- pandas
- matplotlib
- seaborn

---

## 🚀 How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/covid19-global-data-tracker.git
   cd covid19-global-data-tracker
   ```

2. Ensure you have Python and Jupyter installed. You can create a virtual environment (optional):
   ```bash
   python -m venv env
   source env/bin/activate  # On Windows use `env\Scripts\activate`
   pip install -r requirements.txt
   ```

3. Start Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

4. Open the `.ipynb` notebook and run each cell in order to reproduce the analysis.

---

## 📊 Key Insights & Reflections

- **The United States** had the highest total and per capita vaccination count.
- **India** experienced the largest spike in daily new cases during mid-2021, corresponding to the Delta variant surge.
- **Kenya** had a slower start in vaccination rollout but demonstrated steady improvement.
- **Death rates** remained relatively low in Kenya, potentially due to demographics or underreporting.

---

## 📁 Project Structure

```
covid19-global-data-tracker/
├── data/
│   └── owid-covid-data.csv
├── notebook/
│   └── covid19_analysis.ipynb
├── README.md
└── requirements.txt
```

---

## ✅ License

This project is open-source and available under the MIT License.
