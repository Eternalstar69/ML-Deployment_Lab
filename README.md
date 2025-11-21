# ML Deployment Lab

This Project is Sample **Flask Web App** for **Predict House Price in California** With Model **RandomForest** From `scikit-learn`  

---

## Project Structure
```
ml_service/
├── app.py # Flask application
├── model/
│ └── model.pkl 
├── requirements.txt # Dependencies
├── templates/
│ └── main.html 
├── train_model.py 
├── .gitignore
└── README.md
```

---

## Install and Local Usage (VS Code / Local)

1. Clone repository:

```
git clone https://github.com/Eternalstar69/ML-Deployment_Lab.git
cd ML-Deployment_Lab
```
2. Create virtual environment and install dependencies:
```
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```
3. Run Flask App
```
python app.py
```
4. Open Web Browser
```
http://127.0.0.1:5000/
```

**Run With Docker**
---

1.Build Docker image:
```
docker build -t ml-flask-app .
```
2.Run container:
```
docker run -p 5000:5000 ml-flask-app
```
Then Enter URL in Any Browser
```
 http://localhost:5000/
```
