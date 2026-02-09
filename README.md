# 📊 Sentiment Analysis with MLflow

A complete sentiment analysis system for Flipkart product reviews with automatic experiment tracking, model registry, and REST API deployment.

## 🎯 Features
- **MLflow Integration**: Automatic tracking of experiments, parameters, and metrics
- **Multiple Models**: Compare 5+ ML algorithms (Logistic Regression, Random Forest, SVM, etc.)
- **Production API**: Flask-based REST API with real-time predictions
- **Model Registry**: Version control and staging (Development → Staging → Production)
- **Interactive Dashboard**: MLflow UI for experiment visualization
- **Batch Processing**: Analyze thousands of reviews simultaneously
- <img width="509" height="611" alt="image" src="https://github.com/user-attachments/assets/94f42484-36cd-4ccd-ac87-d23ac8d43ac7" />
- <img width="475" height="647" alt="image" src="https://github.com/user-attachments/assets/d2d27744-2e09-4ee1-8484-e541fd8dab14" />
<img width="451" height="458" alt="image" src="https://github.com/user-attachments/assets/1a018e03-0834-42fa-94aa-69a3c7fa272b" />

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
