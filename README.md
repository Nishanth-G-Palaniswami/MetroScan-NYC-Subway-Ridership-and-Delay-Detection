# MetroScan — NYC Subway Ridership and Delay Detection 🚇

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nishanth-G-Palaniswami/MetroScan-NYC-Subway-Ridership-and-Delay-Detection/blob/main/MetroScan_NYC_Subway_Ridership_and_Delay_Detection.ipynb)

An **end-to-end PySpark big data pipeline** that processes **60M+ hourly NYC MTA ridership records** to detect transit delays and anomalies.  

Implements:
- Rolling-window anomaly detection
- PCA + K-Means station clustering
- Gradient Boosted Tree (GBT) regression (RMSE ≈ 104) for delay proxies  
Live interactive visualizations are available in Google Colab.

---

## 📌 Highlights
- **Big Data Processing**: 60M+ rows using PySpark ETL
- **Advanced Analytics**: Rolling average anomaly flagging
- **ML Models**: PCA/K-Means for clustering, GBT for prediction
- **Visual Insights**: Plotly & Matplotlib dashboards in Colab

---

## 📂 Project Structure

├── .gitignore # Ignore unnecessary files

├── LICENSE # MIT License

├── README.md # Project documentation

├── [requirements.txt](requirements.txt) # Dependencies

└── MetroScan_NYC_Subway_Ridership_and_Delay_Detection.ipynb # Main notebook


---

## ⚙️ Installation & Setup

1. Clone this repository
git clone https://github.com/Nishanth-G-Palaniswami/MetroScan-NYC-Subway-Ridership-and-Delay-Detection.git
cd MetroScan-NYC-Subway-Ridership-and-Delay-Detection

2. Install dependencies
   
pip install -r requirements.txt

3. Run in Colab
Click the "Open in Colab" badge above and follow the notebook cells.

📊 Data
Source: [NYC MTA Turnstile Data](http://web.mta.info/developers/turnstile.html)

Data is not included in the repo due to size. The notebook automatically downloads and processes it.

🚀 Usage
Open the notebook in Colab.

Run all cells to:

Load and clean data

Detect anomalies in ridership

Cluster stations based on patterns

Predict delays using GBT

🛠 Requirements
Python 3.8+

PySpark

Pandas, NumPy

Scikit-learn

Matplotlib, Plotly

PyArrow

(See requirements.txt for full list)

📜 License
This project is licensed under the MIT License

👤 Author
Nishanth Ganapathy Palaniswami

📧 ng3124@nyu.edu
💼 [LinkedIn](www.linkedin.com/in/nishanth-g-palaniswami)

