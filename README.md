# Body-Weight Level Prediction

![Project Banner](https://via.placeholder.com/1200x400?text=Body-Weight+Level+Prediction)

## 📌 Project Overview
This project is a **multi-class classification model** that predicts a user's weight category based on their physical attributes and lifestyle habits. It was developed as part of my **3-1 first assignment** in **Machine Learning**. The dataset used for this project was sourced from the **UCI Machine Learning Repository**.

## 🚀 Features
- Predicts body weight levels based on user input.
- Utilizes **Gradient Boosting Model** for accurate classification.
- Implements **Streamlit** for an interactive and user-friendly web application.
- Processes both numerical and categorical inputs using **ColumnTransformer**.

## 🛠 Tech Stack
- **Python**
- **Scikit-Learn**
- **Streamlit**
- **Pandas & NumPy**
- **Pickle** (for model persistence)

## 📂 Project Structure
```
├── weight_level_prediction_model.ipynb  # Model development and training
├── weight_level_prediction_app.py       # Streamlit web app script
├── gradient_boosting_model.pkl          # Trained model file
├── label_encoder.pkl                     # Label encoder for classification mapping
├── column_transformer.pkl                # Column transformer for feature processing
├── README.md                             # Project documentation
```

## 🎮 How to Run the Project
### 1️⃣ Install Dependencies
Make sure you have **Python 3.8+** installed, then run:
```bash
pip install -r requirements.txt
```
_(If `requirements.txt` is not available, manually install:_
```bash
pip install streamlit scikit-learn pandas numpy
```
_)

### 2️⃣ Run the Streamlit App
```bash
streamlit run weight_level_prediction_app.py
```

## 📊 Dataset
The dataset contains various physical and behavioral attributes of individuals, including:
- **Age, Height, Weight**
- **Dietary habits (e.g., vegetable consumption, meal frequency)**
- **Physical activity levels**
- **Technology usage time**
- **Family history and lifestyle habits**

## 🎯 Model Performance
- **Algorithm Used:** Gradient Boosting Classifier
- **Accuracy Achieved:** ~90% (on test data)
- **Feature Engineering:** Applied encoding for categorical features and scaling for numerical features.

## 🖼 App Interface
The Streamlit app provides an intuitive UI where users input their details via sliders and dropdowns to get an instant prediction of their body weight category.

![App Screenshot](https://via.placeholder.com/800x400?text=App+Screenshot)

## 🏆 Future Enhancements
- Improve model accuracy with additional feature engineering.
- Expand the dataset for better generalization.
- Deploy the app using **Heroku** or **Streamlit Cloud**.

## 💡 Acknowledgments
- **UCI Machine Learning Repository** for dataset.
- Inspiration from various ML classification projects.

## 🤝 Connect with Me
Let's connect and improve this project together! 🚀

📧 Email: [seeramneeraj2005@gmail.com](seeramneeraj2005@gmail.com)  
🔗 LinkedIn: [www.linkedin.com/in/seeram-neeraj-kumar-a2a56b267](www.linkedin.com/in/seeram-neeraj-kumar-a2a56b267)  
🐙 GitHub: [(https://github.com/IAMNEERAJ05)](https://github.com/IAMNEERAJ05)

