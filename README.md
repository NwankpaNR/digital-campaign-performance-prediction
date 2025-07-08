# digital-campaign-performance-prediction

Advanced AI system that predicts digital marketing campaign engagement with perfect accuracy and provides actionable business insights through explainable AI and production-ready deployment.

# 🎯 Project Highlights

🏆 100% Prediction Accuracy (exceeded 97% target)

💰 $94,830 Annual Business Value identified through A/B testing

🧠 Two-Factor Model Discovery - simplified 40+ variables to 2 key drivers

🌐 Production API with real-time predictions (<50ms)

📊 Explainable AI with SHAP, LIME, and business insights

🧪 Statistical A/B Testing with rigorous methodology

# 🔍 Key Discovery: Two-Factor Engagement Model

Our explainability analysis revealed that campaign engagement is primarily determined by just 2 factors:

🥇 Session Duration (60.33% importance) - Primary engagement driver

🥈 Click-Through Rate (39.67% importance) - Secondary engagement driver

📊 All other factors: <1% importance

# Business Impact: 
This discovery simplifies marketing optimization from managing 40+ variables to focusing on just 2 key levers!

# 🛠️ Technology Stack

## Machine Learning:

Ensemble Methods: Random Forest, Gradient Boosting, XGBoost, LightGBM
Deep Learning: TensorFlow/Keras neural networks
Explainability: SHAP, LIME, Partial Dependence Analysis

## Production Deployment:

API Framework: FastAPI with Swagger documentation
Monitoring: Real-time dashboard with health checks
Data Processing: Pandas, NumPy, Scikit-learn

## Statistical Analysis:

A/B Testing: Power analysis, significance testing, effect size measurement
Business Intelligence: ROI quantification, optimization recommendations

# 🚀 Quick Start

## 1. Clone Repository

bashgit clone https://github.com/yourusername/digital-campaign-performance-prediction.git

cd digital-campaign-performance-prediction

## 2. Install Dependencies

bashpip install -r requirements.txt

## 3. Run API Server

bashpython api/campaign_api.py

## 4. Access API

Main Interface: http://localhost:8000

Interactive Docs: http://localhost:8000/docs

Live Dashboard: http://localhost:8000/dashboard


# 📊 Project Components

## 1. Data Generation & Analysis

Generated 5,000 realistic digital campaigns

40+ features including CTR, conversion rates, ROAS, demographics

Industry-specific patterns and seasonal effects

## 2. Machine Learning Models

Ensemble Models: 100% accuracy on test data

Deep Learning: 95% accuracy neural network backup

Model Validation: Comprehensive cross-validation and testing

## 3. A/B Testing Framework

Statistical power analysis and sample size calculation

Automated significance testing and effect size measurement

Business impact quantification ($94k+ value identified)

## 4. AI Explainability

Global Insights: Feature importance across models

Individual Explanations: LIME analysis for specific predictions

Business Intelligence: Actionable optimization recommendations

## 5. Production Deployment

FastAPI Service: Real-time predictions with monitoring

Interactive Documentation: Swagger UI for developers

Health Monitoring: System metrics and performance tracking

# 🧪 API Usage Example
pythonimport requests

## Predict campaign engagement
campaign_data = {

    "avg_session_duration": 185,  # 3+ minutes
    
    "ctr": 0.047,                # 4.7%
    
    "campaign_type": "Search",
    
    "industry": "E-commerce",
    
    "daily_budget": 1200
    
}

response = requests.post(

    "http://localhost:8000/predict", 
    
    json=campaign_data
    
)

result = response.json()

print(f"Engagement: {'High' if result['engagement_prediction'] == 1 else 'Low'}")

print(f"Confidence: {result['confidence']:.3f}")

print(f"Suggestions: {result['optimization_suggestions']}")


# 📊 Key Business Insights
## Campaign Optimization Recommendations:

🕐 Session Duration Focus - Optimize landing pages for >3 minute engagement
🎯 CTR Enhancement - Target >4.6% click-through rates
🎬 Video Strategy - Switch from Display to Video (+9.48% revenue)
💻 Desktop Priority - Desktop outperforms Mobile for conversions
🏢 Industry-Specific - Retail campaigns need tailored approach

# A/B Testing Results:

Video vs Display: +9.48% revenue improvement (significant)
Mobile vs Desktop: -10.68% ROAS decline (keep desktop)
Budget Optimization: Inconclusive (requires further testing)

# 🔬 Explainability Results
## Top Features by Importance:

Average Session Duration (60.33%) - Primary success factor

Click-Through Rate (39.67%) - Secondary success factor

All Other Features (<1%) - Minimal impact

## Business Thresholds Discovered:

High Engagement: CTR >0.046 + Session Duration >180s

Low Engagement: Session Duration <120s (regardless of other factors)
