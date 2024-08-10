# 🍃 Plant Disease Classifier 
- A simple Image classification project built to detect, types of diseases the plant might have.
- **Dataset** used to train the model is from Kaggle : [Plantvillage dataset](https://www.kaggle.com/datasets/abdallahalidev/plantvillage-dataset/suggestions?status=pending&yourSuggestions=true) 
- Model Training:  **Convolutional Neural Network (CNN)**
- Easily deployed the model in a containerized environment, **Dockerfile** for reproducability.

## Demo Video 

https://github.com/user-attachments/assets/9d4a84c5-7334-4325-99c8-d4233fff936d

## Quick Start Guide
Clone the repository.

```bash
  git clone https://github.com/br1xn/Plant-Disease-Classifier.git
```

Change directory to app folder

```bash
    cd Plant-Disease-Classifier
    cd app
```
Build the docker Image and run it.

```bash
  docker build -t streamlit-app .
  docker run -p 8501:8501 streamlit-app
```
Alternatively

```bash
  pip install -r requirements.txt
  streamlit run main.py
```
