# AI-Powered-Fraud-Detection
A hybrid fraud detection pipeline using LLM-style embeddings (mocked for local runs) + engineered features and an XGBoost classifier.
It includes a FastAPI model server, a training script using synthetic data, and a Streamlit demo.

## Features
- Synthetic dataset generator for transactions
- Embedding pipeline 
- XGBoost classifier combining embeddings + engineered features
- SHAP explanations + LLM-style rationales 
- FastAPI `/score` endpoint and demo Streamlit UI

