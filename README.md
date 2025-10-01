#In this project, I developed a machine learning–based approach to stock fair value prediction that goes beyond the traditional Graham method (which relies only on EPS and Book Value). By combining multiple financial indicators — such as Debt-to-Equity Ratio, Dividend per Share, ROE, Operating Margin, Net Profit Margin, Free Cash Flow, Enterprise Value-to-Sales, P/E, P/B, and ROA — into a single intrinsic value score, the model provides a comprehensive overview of a stock’s true worth. Instead of analyzing each metric individually, investors can use this unified score as a summary measure, making it easier to identify undervalued or overvalued stocks and make informed investment decisions.

Developed a regression model (R² = 95%, MAPE = 13%) using XGBoost, where the intrinsic value represents a single synthesized score that summarizes multiple financial indicators, making it easier for investors to assess fair value without evaluating each ratio separately.

Applied feature engineering, outlier treatment, VIF multicollinearity checks, and Stats OLS validation to ensure robust model performance.

Utilized SHAP analysis to interpret model predictions and explain how each financial feature contributes to intrinsic value.

Built an automated ML pipeline covering preprocessing, feature engineering, model training, and evaluation.

Tools & Libraries: Python (Pandas, NumPy, Scikit-learn, XGBoost, SHAP, yfinance, VIF, Statsmodels OLS), Jupyter Notebook
