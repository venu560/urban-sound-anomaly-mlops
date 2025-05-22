# Urban Sound Anomaly MLOps

An end-to-end MLOps pipeline for real-time environmental sound anomaly detection using free and open-source tools.

## 🚀 Project Overview

This project demonstrates a complete MLOps workflow for detecting anomalies in urban soundscapes. Using the UrbanSound8K dataset, the pipeline automates data ingestion, feature extraction, model training, deployment, monitoring, and automated retraining. The entire solution is built using only free and open-source tools and is deployable on free cloud platforms.

## ✨ Features

- Automated data ingestion and preprocessing from open datasets
- Audio feature extraction using librosa
- Anomaly detection model training and evaluation
- Experiment tracking with MLflow
- CI/CD automation with GitHub Actions
- Model deployment using Streamlit Community Cloud or Hugging Face Spaces
- Monitoring dashboard for live predictions and model performance
- Automated retraining and redeployment

## 🗂️ Project Structure

urban-sound-anomaly-mlops/
├── data/             # Raw and processed audio data
├── src/              # Source code for data processing, model training, etc.
│   ├── data_ingestion.py
│   ├── feature_engineering.py
│   ├── train_model.py
│   ├── evaluate_model.py
│   └── inference.py
├── models/           # Saved models and checkpoints
├── deployment/       # Deployment scripts and Streamlit app
│   └── streamlit_app.py
├── monitoring/       # Monitoring and dashboard scripts
│   └── dashboard.py
├── notebooks/        # Jupyter notebooks for exploration
├── docs/             # Documentation and diagrams
├── README.md         # Project documentation



## 🛠️ Tech Stack

- Python, pandas, numpy
- librosa (audio processing)
- scikit-learn, TensorFlow or PyTorch (ML)
- MLflow (experiment tracking)
- Docker (containerization)
- Streamlit or Hugging Face Spaces (deployment)
- GitHub Actions (CI/CD automation)

## 📈 How to Use

1. Clone this repository.
2. Set up a Python virtual environment and install dependencies.
3. Download the UrbanSound8K dataset and place it in the `data/` folder.
4. Run the data ingestion and feature extraction scripts.
5. Train the anomaly detection model.
6. Deploy the model as a Streamlit app.
7. Monitor predictions and model performance via the dashboard.
8. Use GitHub Actions for automation and retraining.

## 📚 References

- [UrbanSound8K Dataset](https://urbansounddataset.weebly.com/urbansound8k.html)
- [librosa Documentation](https://librosa.org/doc/latest/index.html)
- [Streamlit Documentation](https://docs.streamlit.io/)
- [MLflow Documentation](https://mlflow.org/)

## 📝 License

This project is for educational purposes and uses only open datasets and free tools.

---

*Project maintained by [Venu M].*
