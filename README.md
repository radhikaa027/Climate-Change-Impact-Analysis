# Climate Change Impact Analysis: A Comparative Study of Chicago and Miami (2010-2022)

## 📌 Project Overview
This project analyzes the effects of climate change in two major U.S. cities, **Chicago** and **Miami**, over a 13-year period (2010-2022). The analysis focuses on key environmental parameters such as **temperature trends, UV index variations, precipitation patterns, and wind speed dynamics**. Using advanced data visualization and statistical methods, this study aims to uncover trends, correlations, and anomalies that impact urban sustainability and climate resilience.

## 📊 Key Findings & Visualizations
### 1️⃣ Cross-Correlation Analysis
- Heatmaps generated to understand relationships between climate variables.
- Example: The correlation between **UV index and temperature** showed a strong seasonal trend.

### 2️⃣ Climate Variability & Trends
- **Temperature fluctuations** indicate a rising trend in Miami, while Chicago shows significant seasonal shifts.
- **Precipitation patterns** reveal increasing rainfall variability in both cities.

### 3️⃣ Clustering Analysis (Fuzzy C-Means)
- Miami and Chicago exhibit distinct climate clusters based on **temperature and UV radiation**.
- Clustering highlights seasonal shifts and long-term climate changes.

### 4️⃣ Regression Models
- Joint regression plots demonstrate the relationship between **surface temperature and atmospheric temperature variations**.
- Predictive models suggest that **Miami's warming trend is more pronounced** compared to Chicago.

## 📡 Data Sources
- **NASA POWER Dataset**: https://power.larc.nasa.gov/data-access-viewer/
- **Chicago Climate Data**: [Google Drive Link](https://drive.google.com/file/d/1iA-Q-Cu0LbsosvYgXMloCDpHDaprNiNt/view?usp=drive_link)
- **Miami Climate Data**: [Google Drive Link](https://drive.google.com/file/d/1sTutCs8upCmD8lCRrROEPzJA6hyI6TQF/view?usp=drive_link)

## ⚙️ Installation & Dependencies
To set up the project, install the required dependencies using:
```bash
pip install -r requirements.txt
```
### Required Libraries:
- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `statsmodels`
- `jupyter`

## 🚀 How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/climate-change-analysis.git
   cd climate-change-analysis
   ```
2. Open Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
3. Navigate to `notebooks/` and run the notebooks sequentially.
4. For automated execution, run:
   ```bash
   python src/data_loader.py
   python src/visualization.py
   ```

## 🔮 Future Scope
- **Expand Analysis:** Include more environmental parameters such as humidity, dew point, and wind patterns.
- **Machine Learning Models:** Use deep learning techniques to predict future climate trends.
- **Real-Time Data Streaming:** Implement API integration for real-time climate monitoring.


## 📜 Citation
If you use this project in your research, please cite:
```
@article{climate2023,
  title={Climate Change Impact Analysis in Miami and Chicago},
  author={Aggarwal, D., Bhati, R., Sayantan, S., Kumari, S.},
  year={2023},
  journal={BML Munjal University Project Report}
}
```

## 📄 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
⭐ Feel free to fork this repository, open issues, and contribute to the project!
