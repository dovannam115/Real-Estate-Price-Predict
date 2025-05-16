# Real Estate Price Prediction

This project leverages Apache Spark and machine learning models to predict real estate prices. It efficiently processes large-scale property datasets and applies regression techniques to estimate property values based on key features such as location, size, and type.

## 🔍 Project Overview

The goal is to build a scalable and accurate pipeline for property price forecasting. Using Spark's distributed computing, the system can process large datasets for both real-time and batch-based predictions.

## 🧰 Technologies Used

- **Apache Spark**: Distributed data processing and ML
- **Python**: Core programming language
- **PySpark MLlib**: Machine learning library for Spark
- **BeautifulSoup & Scrapy**: Web scraping
- **Pandas & NumPy**: Data handling and computations
- **Matplotlib & Seaborn**: Visualization

## 📁 Project Structure

```
Real-Estate-Price-Predict/
├── data/                   # Raw and processed datasets
├── model/                  # Trained models
├── config/                 # Config files
├── description/            # Documentation
├── index/                  # Indexing
├── app.py                  # Main prediction app
├── clean_data.py           # Data cleaning script
├── crawl_data.py           # Scrape property listings
├── crawl_url.py            # URL crawler
├── feature_extract.py      # Feature engineering
├── train_model.py          # Model training
├── utils.py                # Helper functions
├── requirements.txt        # Dependencies
└── README.md               # Project description
```

## 🚀 Getting Started

### Prerequisites

- Python 3.6+
- Apache Spark
- Java 8+

### Installation

```bash
git clone https://github.com/dovannam115/Real-Estate-Price-Predict.git
cd Real-Estate-Price-Predict
pip install -r requirements.txt
```

Ensure Apache Spark is properly installed and configured.

## 🧪 Usage

**1. Crawl data:**

```bash
python crawl_data.py
```

**2. Clean data:**

```bash
python clean_data.py
```

**3. Feature extraction:**

```bash
python feature_extract.py
```

**4. Train model:**

```bash
python train_model.py
```

**5. Run prediction:**

```bash
python app.py
```

## 📊 Features

- Fast data processing with Spark
- Automated data scraping
- Data cleaning and transformation
- Feature engineering
- Regression-based price prediction
- Scalable pipeline

## 📈 Model Evaluation

The model is evaluated using metrics like:

- MAE (Mean Absolute Error)
- MSE (Mean Squared Error)
- R² (R-squared)

## 🤝 Contributing

Contributions are welcome! Feel free to fork and submit pull requests.

## 📄 License

This project is licensed under the MIT License. See `LICENSE` for details.

## 📬 Contact

For questions or suggestions, contact [dovannam](mailto:dovannama5qtk48@gmail.com)
