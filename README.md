# MetroScan-NYC-Subway-Ridership-and-Delay-Detection

MetroScan — NYC Subway Ridership &amp; Delay Detection: End-to-end PySpark pipeline over 60M+ hourly MTA records with rolling-window anomaly detection, PCA/K-Means station clustering, and GBT regression (RMSE ≈ 104) for delay proxies; live visuals in Colab.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](
https://colab.research.google.com/github/Nishanth-G-Palaniswami/MetroScan-NYC-Subway-Ridership-and-Delay-Detection/blob/main/MetroScan_NYC_Subway_Ridership_and_Delay_Detection.ipynb)

## Highlights
- 60M+ rows; PySpark ETL + window functions  
- Rolling anomaly detection (z-score/IQR)  
- PCA-reduced features → K-Means station typologies  
- GBT regression as delay proxy (RMSE ≈ 104)  
- Colab notebook with inline visuals

## Requirements
`pyspark, pandas, numpy, scikit-learn, matplotlib, plotly, pyarrow`

## Run in Colab
Click the badge above and run all cells. Update the data path cell if needed.
