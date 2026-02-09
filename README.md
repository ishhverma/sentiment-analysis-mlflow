# 📊 Sentiment Analysis with MLflow

A complete sentiment analysis system for Flipkart product reviews with automatic experiment tracking, model registry, and REST API deployment.

## 🎯 Features
- **MLflow Integration**: Automatic tracking of experiments, parameters, and metrics
- **Multiple Models**: Compare 5+ ML algorithms (Logistic Regression, Random Forest, SVM, etc.)
- **Production API**: Flask-based REST API with real-time predictions
- **Model Registry**: Version control and staging (Development → Staging → Production)
- **Interactive Dashboard**: MLflow UI for experiment visualization
- **Batch Processing**: Analyze thousands of reviews simultaneously

## 📊 Performance
- **Best Model Accuracy**: 91.84%
- **Dataset**: 8,518 Flipkart product reviews
- **Classes**: Positive, Negative, Neutral
- **Prediction Latency**: <100ms

## 🚀 Quick Start
1. **Clone repository**
2. **Install dependencies**: `pip install -r requirements.txt`
3. **Run training**: `python src/train.py`
4. **Start MLflow UI**: `mlflow ui --port 5000`
5. **Start API**: `python src/api.py`

## 🛠️ Tech Stack
- **MLflow** - Experiment tracking & model management
- **Scikit-learn** - Machine learning algorithms
- **Flask** - REST API framework
- **NLTK** - Natural language processing
- **Pandas/Numpy** - Data processing
- **Plotly** - Interactive visualizations

## 📁 Project Structure
```
sentiment-analysis-mlflow/
├── data/           # Datasets
├── notebooks/      # Jupyter notebooks
├── src/           # Source code (training, API, utils)
├── tests/         # Unit tests
├── requirements.txt
└── README.md
```

## 🔌 API Endpoints
- `POST /predict` - Single text sentiment analysis
- `POST /batch_predict` - Multiple texts analysis
- `GET /health` - API health check
- `GET /model/info` - Model information

## 🎯 Use Cases
- E-commerce product review analysis
- Customer feedback sentiment tracking
- Social media monitoring
- Brand reputation management

## 📝 License
MIT License - See LICENSE file for details


---

**Start analyzing sentiments with professional ML tracking today!** 🚀
