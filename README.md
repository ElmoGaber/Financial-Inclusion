# Financial Inclusion Econometric Analysis

![License](https://img.shields.io/badge/License-MIT-yellow.svg)
![Python](https://img.shields.io/badge/Python-3.x-blue)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)
![Econometrics](https://img.shields.io/badge/Econometrics-Time%20Series-blueviolet)

**Comprehensive econometric study** of the determinants of Financial Inclusion in a developing economy using annual time-series data (2010–2024). The analysis focuses on realistic model specification, robust inference, and diagnostic validation to identify key macroeconomic and institutional drivers of FI.

---

## ✨ Project Highlights

- Time-series dataset covering 15 years (2010–2024)  
- Realistic variable selection avoiding perfect multicollinearity and overfitting  
- Application of robust standard errors (Newey-West HAC) to handle autocorrelation  
- Thorough diagnostic tests: stationarity, cointegration, serial correlation, heteroskedasticity  
- Final model interpretation with economic significance and policy implications  
- Visualizations of trends, correlations, model fit, and residual diagnostics  
- Full reproducibility using Jupyter Notebook  
- Exportable regression tables and econometric results (Excel & images)  
- Focus on practical policy-relevant findings rather than mechanical significance  

---

## 📊 Key Files in the Repository

- `Notebook.ipynb` → Complete analysis workflow (data prep → modeling → diagnostics → interpretation)  
- `Comprehensive Explanation of the Code.pdf` → Detailed walkthrough of methodology and code logic  
- `econometric_results.xlsx` → All regression outputs, coefficients, p-values, diagnostics  
- `financial_inclusion_final_model.png` → Visualization of the final estimated model  
- `احصائيات البحث-جديد -النموذج القياسى.xlsx` → Supplementary statistics and intermediate model results  
- `README.md` → Project overview and context  

---

## 🚀 Quick Start

1. Clone the repository  
   ```bash
   git clone https://github.com/ElmoGaber/Financial-Inclusion.git
   cd Financial-Inclusion
   ```

Open the notebookBashjupyter notebook Notebook.ipynb
Install required packages (if needed)Bashpip install pandas numpy statsmodels matplotlib seaborn openpyxl
Run all cells sequentially to reproduce the full analysis


📈 Methodology Overview

Data: Annual time-series (15 observations, 2010–2024)
Dependent Variable: Financial Inclusion Index (composite or proxy measure)
Independent Variables: GDP growth, inflation, interest rate spread, mobile penetration, institutional quality, remittances, etc.
Estimation Technique: OLS with robust covariance (Newey-West)
Stationarity: ADF / KPSS tests applied where appropriate
Model Selection: Stepwise + theoretical justification (avoid mechanical selection)
Diagnostics: Breusch-Godfrey, White test, RESET, normality checks
Robustness: Alternative specifications and sensitivity checks

```
📁 Repository Structure
textFinancial-Inclusion/
├── Notebook.ipynb                        # Main analysis notebook
├── Comprehensive Explanation of the Code.pdf   # Detailed code & method explanation
├── econometric_results.xlsx              # Regression tables & statistics
├── financial_inclusion_final_model.png   # Final model visualization
├── احصائيات البحث-جديد -النموذج القياسى.xlsx   # Additional stats & model outputs
├── README.md
└── ...
```
🎯 Main Findings (Summary)

Positive and significant effect of mobile phone penetration on financial inclusion
Remittances show consistent positive contribution to FI
Institutional quality (rule of law, control of corruption) emerges as a strong driver
Inflation and high interest rate spreads act as barriers
GDP growth has expected positive but sometimes muted effect due to data limitations
Model passes major diagnostic tests after applying HAC standard errors
Results are robust to alternative variable inclusions/exclusions


📸 Visualizations Included

Time series plots of FI and key explanatory variables
Correlation heatmap
Residual diagnostics (ACF/PACF, Q-Q plots)
Actual vs. fitted values
Coefficient plots with confidence intervals

See financial_inclusion_final_model.png for the core model summary visualization.



📄 License
MIT License — see the LICENSE file (or assume standard MIT terms if not present).
You are free to use, modify, share, and build upon this work for academic, research, or policy purposes.

🙏 Acknowledgments

Inspired by World Bank / IMF financial inclusion studies
Thanks to statsmodels for powerful time-series and econometric tools in Python
Gratitude to researchers working on FI in developing economies


Built with ❤️ by ElmoGaber
