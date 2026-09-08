# 2020 A/L Dataset Profiling

##  Student Information
- Index: GAHDSE25.2F-29  

##  Technologie  
- Pandas, NumPy  
- YData Profiling  

##  Features
- Dataset loading & preprocessing  
- Missing/duplicate record detection  
- Data type & unique value analysis  
- Numerical & categorical statistics  
- Rank data extraction & conversion  
- Automated HTML profiling report  

##  Progress
1. **ETL – Extraction** → Dataset load into DataFrame  
2. **ETL – Transformation** → Null rows remove + Zscore convert to float64  
3. **Analysis** → Column overview, descriptive stats, bar plots by stream  

##  Files
- `profile_data.py` → Main script  
- `profile_column_health.csv` → Missing-value summary  
- `profile_numeric_summary.csv` → Numerical stats  
- `dataset_profiling_report.html` → Interactive report  
- `requirements.txt` → Dependencies  
- `.gitignore` → Excluded files  
