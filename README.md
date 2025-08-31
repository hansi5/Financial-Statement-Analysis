# Financial Statement Analysis Web Application  

A Flask-based web application to perform **financial ratio analysis** from Profit & Loss statements and Balance Sheets. The app allows users to input financial data, automatically compute ratios, visualize trends, and generate reports for both **1-year and 5-year periods**.  

🔗 **Live Demo:** [View]([https://your-render-app-url](https://financial-statement-analysis.onrender.com/))  

---

## Features  
- **Data Input Forms** – Input Profit & Loss (P&L) and Balance Sheet (B/S) data.  
- **Ratio Calculations** – Automatically compute profitability, liquidity, solvency, and leverage ratios.  
- **Error Handling** – Detects division errors and unbalanced balance sheets.  
- **5-Year Comparison** – Analyze max, min, and average ratios over 5 years.  
- **Visual Reports** – Displays ratio definitions, formulas, and interpretations.  
- **Email Integration** – Users can send messages through the contact form (SMTP).  
- **Responsive UI** – Built using **Flask + Bootstrap** for clean design.  
- **Deployed on Render** – Accessible online without local setup.  

---

## Tech Stack  
- **Backend:** Flask, Python (Pandas, NumPy, Matplotlib, JSON, dotenv)  
- **Frontend:** HTML, CSS, Bootstrap, Jinja2 Templates  
- **Data Analytics & Visualization:** Pandas, NumPy, Matplotlib  
- **Other:** SMTP (email support), Custom Exception Handling  
- **Deployment:** Render  

---

## Ratios Implemented  

### Profit & Loss Ratios  
- Gross Profit Ratio  
- Net Profit Ratio  
- Operating Profit Ratio  

### Balance Sheet Ratios  
- Current Asset Ratio  
- Quick Asset Ratio  
- Long Term Debt to Equity Ratio  
- Total Debt to Equity Ratio  
- Proprietary Ratio  

---

## Contact Feature  
- Uses **SMTP** to send messages directly from the web app.  
- Requires valid Gmail credentials (App Password recommended).  

---

## Future Improvements  
- Add database support (**MySQL/PostgreSQL**) instead of JSON.  
- Export reports as **PDF/Excel**.  
- Add **authentication** for user-specific analysis.  

