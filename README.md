# IMDb Review Sentiment Analysis 🎥📊

## 📄 Problem Statement
The aim of this project is to classify IMDb movie reviews into **positive** or **negative** sentiment categories. With a review as input, the model predicts the sentiment, enabling applications such as **customer feedback analysis**, **social media sentiment tracking**, and **sentiment-based recommendations**.

---

## 🎯 Objective
To develop a **Transformer-based Sentiment Analysis Pipeline** that:
1. **Processes raw text** from IMDb movie reviews.
2. **Classifies text** into positive or negative sentiment.
3. Provides an interactive **user-friendly interface** for predictions.

---

## 🛠️ Technological Stack
This project leverages the following tools and technologies:

### Programming & Libraries
- **Python** 🐍: Backend logic and scripting.
- **Hugging Face Transformers** 🤗: State-of-the-art pre-trained language models For seamless model integration and fine-tuning.
- **PyTorch** 🔥: Deep learning computations and model operations.

### Development Tools
- **Streamlit**: For building a web-based interactive user interface.
- **ZenML** 🛠️: MLOps pipeline automation, including data ingestion and model deployment.
- **MLflow** 📊: Experiment tracking, model versioning, and performance monitoring.

### Deployment Tools
- **Docker** 🐳: Containerizing the application for scalable deployment.

---

## 📚 Dataset Overview
The dataset used in this project is the **IMDb Movie Reviews Dataset**, comprising 50,000 labeled movie reviews:
- **Positive Sentiment** 😊: Reviews reflecting satisfaction.
- **Negative Sentiment** 😔: Reviews expressing dissatisfaction.

### Challenges in the Dataset
- **Noisy Text**: Reviews contain HTML tags, links, emojis, and special characters requiring preprocessing.
- **Ambiguity in Sentiments**: Mixed sentiments in some reviews pose challenges for classification.


## 🏗️ Project Architecture
The project follows a structured workflow:
1. **Data Preprocessing**:
   - Remove HTML tags, links, emojis, and other noise.
   - Normalize text for better model input.
2. **Model Training**:
   - Fine-tune pre-trained Hugging Face Transformers on the IMDb dataset.
3. **Evaluation**:
   - Measure performance using metrics like accuracy, precision, recall, and F1 score, tracked with MLflow.
4. **Deployment**:
   - Build scalable MLOps pipelines using ZenML and deploy with Docker.
5. **User Interface**:
   - Enable real-time text classification via a Streamlit-based web app.

---

## 🌟 Features
- **Real-Time Sentiment Prediction**: Classify movie reviews with confidence scores.
- **Intuitive UI**: Interactive app for ease of use.
- **Scalable and Reproducible**: Dockerized setup for seamless deployment.
- **MLOps Integration**: Automated workflows with ZenML and experiment tracking with MLflow.

---

## 🛠️ Tools and Technologies Used
- **Python**
- **Transformers** (Hugging Face)
- **PyTorch**
- **Streamlit**
- **ZenML**
- **MLflow**
- **Docker**

---

## 🖼️ Project Architecture
Below is a high-level architectural diagram for the project:

![Project Architecture](path/to/architecture_image.png)

---

## 📥 How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/imdb-sentiment-analysis.git
