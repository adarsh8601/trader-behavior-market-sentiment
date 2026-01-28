**Trader Behavior vs Market Sentiment Analysis**

Project Overview  
This project analyzes trader behavior on the Hyperliquid platform in relation to overall market sentiment, as represented by the Bitcoin Fear & Greed Index. The objective is to understand how sentiment-driven market phases influence trading activity, risk exposure, and profitability.

Folder Structure  
ds\_adarsh\_giri/  
├── notebook\_1.ipynb \# Main analysis and EDA (Google Colab)  
├── notebook\_2.ipynb \# Additional analysis (optional)  
├── csv\_files/ \# Cleaned and processed datasets  
├── outputs/ \# Visualizations and charts  
├── ds\_report.pdf \# Final summarized report  
└── README.md \# Project overview and instructions

Analysis Notebook  
The complete analysis was conducted using Google Colab.

Project Files  
Google Drive Directory (view-only):    
[https://drive.google.com/drive/folders/12c0wV2FqZ-ZqO5SHUrX9pgNpZ7GVUkaC?usp=drive\_link](https://drive.google.com/drive/folders/12c0wV2FqZ-ZqO5SHUrX9pgNpZ7GVUkaC?usp=drive_link)

Google Colab Notebook (view-only):    
[https://colab.research.google.com/drive/178OCkmcr4G1DsVILdbYr0-tAedwbFKtE?usp=sharing](https://colab.research.google.com/drive/178OCkmcr4G1DsVILdbYr0-tAedwbFKtE?usp=sharing)

Datasets Used  
\- **Historical Trader Data:-** Contains trade-level details such as execution price, position size, trade direction, and realized PnL.  
\- **Bitcoin Fear & Greed Index:-** Daily sentiment indicator classifying market conditions into Fear and Greed phases.

Both datasets were cleaned, aligned by date, and merged for analysis.

Tools & Technologies  
\- Python  
\- Pandas, NumPy  
\- Matplotlib, Seaborn  
\- Google Colab

Key Insights (Summary)  
\- Trading activity and volume vary noticeably across different market sentiment phases.  
\- Traders tend to take larger positions during Greed-dominated periods.  
\- Profitability patterns differ between Fear and Greed regimes.  
\- Certain contrarian behaviors show improved performance under specific sentiment conditions.

Detailed insights and supporting visualizations are included in the final report.

How to Run  
1\. Open the Google Colab notebook using the provided link.  
2\. Ensure datasets are available in the \`csv\_files/\` directory.  
3\. Run the notebook cells sequentially to reproduce the analysis and visualizations.

Note  
Raw datasets are not included due to size and source constraints.   
All analysis steps are fully reproducible using the provided notebooks.

Author  
Adarsh Giri

Submission Date  
28 January 2026