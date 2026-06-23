##  Repository Overview

Welcome to my portfolio of data-driven financial research, quantitative analytics, and behavioral economics frameworks. This repository serves as a centralized hub for projects that leverage programming, advanced statistical inference, and cognitive psychology to dissect market trends, evaluate corporate financial health, and optimize digital consumer experiences.

By bridging the gap between rigorous data analysis and strategic decision-making, these projects address complex financial problems, evaluate market efficiency, and architect optimal choice environments for digital-first ecosystems.

---

##  Key Focus Areas

* **Quantitative Finance & Market Research:** Conducting macroeconomic evaluation, valuation rerating, and Earnings Per Share (EPS) variance analysis across volatile emerging stock markets (e.g., KSE-100 index).
* **Statistical Inference & Predictive Modeling:** Applying hypothesis testing, single-factor ANOVA, multiple linear regression, Chi-Square tests, and Two-Proportion Z-tests to identify demographic predictors and isolate product engagement lifts.
* **Corporate Financial Health & Structure:** Performing longitudinal 5-year ratio analysis spanning structural liquidity bottlenecks, capital leverage dependencies, and asset management efficiency against aggregate industry benchmarks.
* **Behavioral Economics & Fintech UX:** Auditing digital onboarding journeys using cognitive friction matrices and designing choice architecture playbooks to bridge the consumer "intention-action gap" in digital banking.

##  Project Directory

### 1. Statistical Analysis of Environmental Determinants of CO2 Emissions per Capita
* **Objective:** Compared the levels of annual per capita CO2 emissions across countries categorized into four distinct income groups for the year 2022 to identify significant driving determinants and differences among groups.
* **Methodology:** Sourced comprehensive environmental and demographic datasets from *Our World in Data* and *Wikipedia*. Executed descriptive statistical summaries, two-sample non-pooled t-tests, and a single-factor ANOVA in **Microsoft Excel** to evaluate variance across income levels. Constructed a multiple linear regression model analyzing the impacts of GDP, energy consumption per capita, population density, and high-income structural dummy variables. Developed visual asset distributions, including right-skewed data histograms and scatter plot matrices, using **R Studio**.
* **Key Insight:** While descriptive and hypothesis testing confirmed that high and upper-middle-income countries produce exponentially larger and more volatile CO2 footprints than lower-income brackets, the regression framework accounted for only 15.67% of cross-country output variance ($R^2 = 0.1567$). At a 5% level of significance, population density emerged as the only statistically sound predictor variable ($p = 0.0423$), proving that narrow macroeconomic indicators act as poor predictors unless coupled with policy and industrialization data.
* **Notebook/File:**  https://github.com/laibadalaiba/Financial-and-Data-Analysis/blob/main/SI%20Analysis.pdf
* **Notebook/File:** https://github.com/laibadalaiba/Financial-and-Data-Analysis/blob/main/SI%20Assignment%20Excel%20Sheet.xlsx
   

  
### 2. The KSE-100 Bull Run: Financial Analysis of Pakistan's 2025 Stock Market Performance
* **Objective:** Investigated the efficiency, fundamentals, and sustainability of the 2025 Pakistan Stock Exchange (PSX) bull run to evaluate whether the market surge reflected true corporate earnings growth or a speculative bubble across major sectors.
* **Methodology:** Collected extensive calendar year 2025 data across banking, cement, oil & gas, and retail sectors from the State Bank of Pakistan (SBP), SECP, IMF, and public corporate filings. Conducted a detailed valuation rerating and Earnings Per Share (EPS) variance analysis for sector leaders (such as HBL, UBL, MCB, PSO, OGDCL, and Maple Leaf Cement). Evaluated macroeconomic stabilization indicators, monetary policy adjustments, and shifting retail investor behavior driving market liquidity.
* **Key Insight:** The analysis revealed a divergence between stock price appreciation and fundamental earnings growth, driven largely by valuation rerating, macroeconomic stabilization, and aggressive retail market entry rather than uniform earnings expansions. While some entities experienced stark valuation compressions or pure expansions despite negative earnings growth, the overall 2025 rally functioned as a highly sentiment-driven re-pricing of sovereign risk following IMF program progress and monetary easing cycles.
* **Notebook/File:** `https://github.com/laibadalaiba/Financial-and-Data-Analysis/blob/main/KSE100_Report.pdf`

### 3. Corporate Financial Health Assessment: Five-Year Analysis of Mirpurkhas Sugar Mills Ltd
* **Objective:** Conducted a comprehensive five-year longitudinal financial performance evaluation (2020–2024) of Mirpurkhas Sugar Mills Ltd (MSML) to assess its structural liquidity, capital leverage efficiency, operational profitability, and overall market position relative to industry benchmarks.
* **Methodology:** Extracted historical financial data and performed structured ratio analysis across five core dimensions: liquidity, asset management, debt leverage, profitability, and market value. Developed a customized multi-criteria scoring matrix (1–5 performance scale) to isolate operational bottlenecks, track macro trends, evaluate times-interest-earned (TIE) ratios under volatile cost structures, and cross-examine firm KPIs against aggregate sugar industry averages.
* **Key Insight:** The analysis identified a stark divergence between surging operational profitability—with a significant net profit growth rebound reaching 18.56% and ROA climbing from 3.63% to 16.09% by 2024—and underlying structural liquidity pressures, marked by persistent sub-1.0 current and quick ratios. This highlighted a high-leverage operating model where short-term debt dependencies and heavy interest obligations (TIE < 1.0 in key periods) strained market valuation metrics and investor sentiment despite strong topline expansions.
* **Notebook/File:** `https://github.com/laibadalaiba/Financial-and-Data-Analysis/blob/main/IBF%20project%20ppt.pdf`

### 4. Predicting Digital-Only Banking Adoption: A Quantitative Fintech Consumer Behavior Study
* **Objective:** Investigated the demographic and behavioral factors that statistically predict a consumer's transition from traditional, branch-based banking to digital-only adoption, while evaluating the quantitative impact of a strategic in-app user interface (UI) redesign on active user engagement.
* **Methodology:** Processed a simulated 1,200-respondent consumer survey calibrated to FDIC, Federal Reserve, and Bankrate macro benchmarks. Applied Chi-Square Tests of Independence and calculated Cramér's V to measure effect sizes across demographic variables (age, income, occupation, and region). Constructed 95% confidence intervals to quantify transaction frequency differentials and executed a Two-Proportion Z-Test to isolate the statistical significance of the UI redesign's engagement lift.
* **Key Insight:** Age emerged as the strongest statistical predictor of digital-only banking adoption (Cramér's V = 0.48), followed by occupation (0.32) and income (0.29), while geographic region proved statistically insignificant. Digital-only users exhibited a 9.2x higher transaction velocity per month compared to branch-dependent users (24.8 vs. 2.7 transactions). Furthermore, the UI redesign achieved a statistically rigorous 8.5% absolute lift in active weekly engagement, rising from 34.0% to 42.5% ($z = 2.91$, one-sided $p < 0.005$), validating data-driven UX improvements as a core retention driver.
* **Notebook/File:** `https://github.com/laibadalaiba/Financial-and-Data-Analysis/blob/main/FinTechConsumerBehaviorAnalysis.pdf`

---

##  How to Run the Projects

To replicate the analysis locally, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/yourusername/your-repo-name.git](https://github.com/yourusername/your-repo-name.git)
