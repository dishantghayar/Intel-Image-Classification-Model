# Image Classification API  

This project trains a CNN model on the Intel Image Classification dataset and deploys it as a FastAPI/Flask API.  
Run `pip install -r requirements.txt`, then train the model using `train.py`.  
Start the API with `python app.py` and send image predictions via `/predict`.  
(Optional) Use Docker: `docker build -t image-classifier . && docker run -p 8000:8000 image-classifier`.  

