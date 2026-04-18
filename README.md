# Understanding Time-Based Data
### A Foundational Tutorial Series for Public Safety Professionals

> **Developed by the [Center for Interdisciplinary Statistical Education and Research (CISER)](https://ciser.wsu.edu) at Washington State University**
> Contact: [yin.zhang@wsu.edu](mailto:yin.zhang@wsu.edu)

---

## About This Series

This tutorial series is designed for **public safety professionals** (law enforcement, analysts, and administrators), **general audiences**, and **early-stage researchers** who want to understand time-based data — without needing a statistics background.

Each topic is a self-contained, one-page module. You can read them in order for a complete foundation, or jump directly to the topic that answers your immediate question. Every topic takes approximately **5 minutes to read**.

All examples use **synthetic data** from two fictional precincts, created for teaching purposes only. They do not represent any real jurisdiction or real incidents.

---

## 📂 Repository Structure

```
📁 Time-Series-Tutorials/
├── 📄 README.md
├── 📁 Beginner/
│   ├── 📄 Complete_Beginner_Series.docx        ← Full series (all 20 topics)
│   ├── 📄 Topic_01_What_is_Time_Series.pdf
│   ├── 📄 Topic_02_Time_Series_vs_Cross_Sectional.pdf
│   ├── 📄 Topic_03_Visualizing_Time_Series.pdf
│   ├── 📄 Topic_04_Time_Units_Frequency_Aggregation.pdf
│   ├── 📄 Topic_05_Counts_vs_Rates.pdf
│   ├── 📄 Topic_06_Missing_Data_Reporting_Gaps.pdf
│   ├── 📄 Topic_07_Trend.pdf
│   ├── 📄 Topic_08_Seasonality.pdf
│   ├── 📄 Topic_09_Cycles_vs_Seasonality.pdf
│   ├── 📄 Topic_10_Noise_and_Irregular_Fluctuations.pdf
│   ├── 📄 Topic_11_Outliers_and_Spikes.pdf
│   ├── 📄 Topic_12_Short_vs_Long_Term_Change.pdf
│   ├── 📄 Topic_13_Smoothing_and_Moving_Averages.pdf
│   ├── 📄 Topic_14_Comparing_Multiple_Series.pdf
│   ├── 📄 Topic_15_Lagged_Effects.pdf
│   ├── 📄 Topic_16_Autocorrelation.pdf
│   ├── 📄 Topic_17_Stationarity.pdf
│   ├── 📄 Topic_18_Year_over_Year_Comparison.pdf
│   ├── 📄 Topic_19_Data_Quality_and_Pitfalls.pdf
│   └── 📄 Topic_20_How_to_Read_a_Chart_Checklist.pdf
├── 📁 Medium/                                   ← Coming Soon
├── 📁 Advanced/                                 ← Coming Soon
└── 📁 Python_Code/                              ← Coming Soon
```

---

## 📘 Beginner Level — Now Available

**No statistics background required. No math. Just concepts and examples.**

### Part I: Foundations — Understanding Time-Based Data
*What is time series data, and how is it structured?*

| # | Topic | Key Question Answered |
|---|-------|-----------------------|
| 1 | [What Is a Time Series?](Beginner/Topic_01_What_is_Time_Series.pdf) | Why does timing matter as much as the total count? |
| 2 | [Time Series vs. Cross-Sectional Data](Beginner/Topic_02_Time_Series_vs_Cross_Sectional.pdf) | What is the difference between a "snapshot" and a "movie"? |
| 3 | [Visualizing Time Series — The Line Plot](Beginner/Topic_03_Visualizing_Time_Series.pdf) | Why is a line plot better than a bar chart for time-based data? |
| 4 | [Time Units, Frequency, and Aggregation](Beginner/Topic_04_Time_Units_Frequency_Aggregation.pdf) | How does the choice of daily vs. monthly data change conclusions? |
| 5 | [Counts vs. Rates Over Time](Beginner/Topic_05_Counts_vs_Rates.pdf) | Does a higher count really mean more danger — or just more activity? |
| 6 | [Missing Time Points and Reporting Gaps](Beginner/Topic_06_Missing_Data_Reporting_Gaps.pdf) | What do you do when a month of data is simply not there? |

### Part II: Patterns — What the Data Is Telling You
*How to recognize and interpret the key patterns in time series data.*

| # | Topic | Key Question Answered |
|---|-------|-----------------------|
| 7 | [Trend — The Long-Term Direction](Beginner/Topic_07_Trend.pdf) | Is the situation really getting worse — or is one bad month misleading us? |
| 8 | [Seasonality — Predictable Patterns](Beginner/Topic_08_Seasonality.pdf) | How do we know if a summer spike is a crisis or just... summer? |
| 9 | [Cycles vs. Seasonality](Beginner/Topic_09_Cycles_vs_Seasonality.pdf) | What is the difference between a pattern that repeats yearly vs. every few years? |
| 10 | [Noise and Irregular Fluctuations](Beginner/Topic_10_Noise_and_Irregular_Fluctuations.pdf) | When should we *not* try to explain a data change? |
| 11 | [Outliers and Spikes](Beginner/Topic_11_Outliers_and_Spikes.pdf) | One extraordinary event inflated our annual average — now what? |
| 12 | [Short-Term Fluctuations vs. Long-Term Change](Beginner/Topic_12_Short_vs_Long_Term_Change.pdf) | How do we avoid reacting to noise as if it were a trend? |
| 13 | [Smoothing and Moving Averages](Beginner/Topic_13_Smoothing_and_Moving_Averages.pdf) | How do we cut through month-to-month noise to see the real signal? |
| 14 | [Comparing Multiple Time Series](Beginner/Topic_14_Comparing_Multiple_Series.pdf) | Is this a local problem or a city-wide problem? |
| 15 | [Lagged Effects — Why Policies Don't Work Instantly](Beginner/Topic_15_Lagged_Effects.pdf) | How long should we wait before deciding a new program is working? |
| 16 | [Autocorrelation — The "Memory" of Data](Beginner/Topic_16_Autocorrelation.pdf) | Why does this month's data tell us so much about next month? |
| 17 | [Stationarity — The Stable Baseline](Beginner/Topic_17_Stationarity.pdf) | What does it mean for data to be "stable" — and why does it matter for forecasting? |
| 18 | [Year-over-Year (YoY) Comparison](Beginner/Topic_18_Year_over_Year_Comparison.pdf) | Why compare to the same month last year instead of last month? |
| 19 | [Data Quality and Common Pitfalls](Beginner/Topic_19_Data_Quality_and_Pitfalls.pdf) | How do we know if an unusual pattern is real — or a data artifact? |
| 20 | [How to Read a Time Series Chart — A Checklist](Beginner/Topic_20_How_to_Read_a_Chart_Checklist.pdf) | What 12 questions should I ask every time I look at a time series chart? |

---

## 🔜 Coming Soon

### Medium Level
Building on the beginner foundations, the Medium level will introduce more formal methods — still accessible, but with more analytical depth. **Uploading soon.**

### Advanced Level
For researchers and analysts who want to apply formal statistical models to public safety data. **Uploading soon.**

### 🐍 Python Code Exercises
Every topic across all levels will be accompanied by a **Python Jupyter notebook** — no prior coding experience required. The notebooks will walk through each concept using the same synthetic dataset, so you can see the numbers come to life in code.

> Python exercises will be available in the `/Python_Code/` folder as each level is published.

---

## 📹 CISER Video Tutorials

The **Center for Interdisciplinary Statistical Education and Research (CISER)** at Washington State University is developing a companion series of **foundational statistics video tutorials**, led by CISER subject-matter experts across multiple disciplines.

These videos cover topics ranging from basic descriptive statistics to regression and beyond — designed for the same broad audience as this written series. They will be announced and linked here as they become available.

---

## 🗂 Who Is This For?

| Audience | How to Use This Series |
|----------|------------------------|
| **Public safety professionals** (commanders, analysts, administrators) | Read individual topics on demand; use the Topic 20 checklist in regular briefings |
| **General public** | Read Part I (Topics 1–6) for a solid intuition about how time-based data works |
| **Early-stage researchers** | Work through all 20 topics in order before moving to the Medium level |
| **Journalists and policy advocates** | Topics 11, 12, 18, and 19 are particularly relevant for critically reading crime statistics |

---

## 📄 License & Citation

This tutorial series is developed for educational purposes and freely available for non-commercial use.

If you use or reference this material, please cite:

> Zhang, Y. (2026). *Understanding Time-Based Data: A Foundational Tutorial Series for Public Safety Professionals.* Center for Interdisciplinary Statistical Education and Research (CISER), Washington State University.

---

## 📬 Contact & Feedback

Questions, errors, suggestions, or collaboration inquiries:

**Yin Zhang**
Center for Interdisciplinary Statistical Education and Research (CISER)
Washington State University
📧 [yin.zhang@wsu.edu](mailto:yin.zhang@wsu.edu)

Your feedback is highly valued — this series is a living document and will be updated based on reader input.
