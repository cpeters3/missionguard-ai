# MissionGuard AI

## Features
- Simulated mission/sensor dataset generation
- Data preprocessing and feature engineering
- Machine learning classification workflow
- Model evaluation with confusion matrix and classification report
- FastAPI deployment for prediction serving
- Basic testing with pytest

## Tools Used
- Python
- pandas
- numpy
- scikit-learn
- matplotlib
- FastAPI
- joblib
- pytest

## Project Workflow
1. Generate mission event data
2. Preprocess and engineer features
3. Train classification model
4. Evaluate performance
5. Save model
6. Serve predictions via API

## How to Run
```bash
python src/simulate_data.py
python src/preprocess.py
python src/train.py
python src/evaluate.py
uvicorn src.api:app --reload
