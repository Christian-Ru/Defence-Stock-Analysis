# Defence Stock Analysis: Impact of the Ukraine Invasion

## 📘 Project Overview

This project analyzes how the stock prices of major **European defence companies** evolved before and after Russia’s invasion of Ukraine in February 2022.
It compares their performance to the **Euro Stoxx 600** benchmark to assess how the geopolitical shock influenced the European defence sector.

The analysis was conducted using **Python**, **pandas**, and **matplotlib** within a Jupyter Notebook environment.

---

## 🧠 Objective

To evaluate how the Russian invasion of Ukraine affected European defence stocks, using historical price data to identify performance and volatility shifts.

---

## 🧩 Data & Tools

* **Data Source:** Yahoo Finance (`yfinance`)
* **Companies Analyzed:**

  * Rheinmetall (RHM.DE)
  * Leonardo (LDO.MI)
  * Airbus (AIR.PA)
  * Safran (SAF.PA)
  * BAE Systems (BAESY)
* **Benchmark:** Euro Stoxx 600 (`^STOXX`)
* **Libraries Used:** pandas, numpy, matplotlib, yfinance

---

## 📊 Key Metrics

* Daily and cumulative returns (%)
* Pre- vs post-invasion performance comparison
* Relative performance vs the Euro Stoxx 600 benchmark

---

## 🕓 Time Period

* **Start date:** 2019-02-24
* **Event date:** 2022-02-24 (Invasion of Ukraine)
* **End date:** Present

---

## 🚀 Results Summary

* **Rheinmetall (Germany)** and **Leonardo (Italy)** recorded the strongest post-invasion gains, reflecting rising European defence budgets.
* **Airbus** and **Safran** remained relatively stable, reflecting diversified exposure to civil aviation.
* **Euro Stoxx 600** underperformed the defence sector overall, highlighting the sector-specific impact of geopolitical risk.

---

## 💻 How to Run

1. Clone this repository:

   ```bash
   git clone https://github.com/Christian-Ru/Defence-Stock-Analysis.git
   ```
2. Install required packages:

   ```bash
   pip install yfinance pandas matplotlib numpy
   ```
3. Open and run the notebook:

   ```bash
   jupyter notebook
   ```

---

## 🧩 Next Steps

* Add interactive visualizations (e.g. Streamlit or Plotly)
* Expand to include U.S. defence contractors for cross-region comparison
* Conduct correlation analysis between defence stocks and energy or commodity indices

---

## 📫 Contact

**Author:** Christian R.
Feel free to connect on [LinkedIn](https://www.linkedin.com/) or reach out via GitHub for feedback and collaboration.
