<<<<<<< HEAD
# Customer Churn Prediction API
 
This project predicts whether a telecom customer is likely to leave the
company using a Random Forest machine learning model, served with FastAPI
and deployed on Render.
## Run Locally
pip install -r requirements.txt
python train_model.py
uvicorn app:app --reload
 
## API
- GET  /         health check
- POST /predict  returns a churn prediction for a JSON customer record
=======
# car-price-api
>>>>>>> 9667df8bf94673dedb23397c9172935be4c35645
