# Crop-and-Fertilizer-recommendation-system
🌾 Crop & Fertilizer Recommendation System

📌 Overview

Farmers often face challenges in selecting the right crop and fertilizer for their soil conditions, leading to lower yields and financial losses. Our Machine Learning-based Crop & Fertilizer Recommendation System leverages machine learning to provide data-driven insights for agricultural decision-making.<br><br>

🎯 Problem Statement

🚜 Farmers struggle to determine suitable crops and fertilizers for their soil conditions, resulting in:

- Inefficient farming due to incorrect crop choices.
- Loss of resources from poor decision-making.
- Lack of precision in manual recommendations.

💡 Solution

Our Machine Learning-based system takes Nitrogen (N), Phosphorus (P), Potassium (K), Temperature, Humidity, pH, and Rainfall as inputs and predicts a suitable crop for cultivation.

🔹 Example Input:

N = 90, P = 42, K = 43
Temperature = 20°C, Humidity = 82%
pH = 6.1, Rainfall = 202 mm

🔹 Predicted Output:

Recommended Crop → Rice 🌾

<br><br>

🔬 Methodology

1️⃣ Dataset Collection

Pre-existing crop dataset containing soil properties & climate conditions.

2️⃣ Data Preprocessing

Handling missing values, feature scaling, and encoding categorical variables where required.

3️⃣ Splitting Data

Dividing data into training & testing sets.

4️⃣ Model Training

Implementing a Decision Tree Classifier for prediction.

5️⃣ Prediction & Evaluation

Assessing accuracy and recommending a suitable crop based on environmental factors.

<br><br>

🛠 Tools & Technologies

Programming Language: Python 🐍

Libraries: NumPy, Pandas, Scikit-learn, Matplotlib 📊

Machine Learning Model: Decision Tree Classifier 🌳

Development Environment: Jupyter Notebook / Google Colab 📓

Dataset: Crop Dataset 🌱

<br><br>

📊 Dataset Overview

The crop dataset contains the following agricultural parameters:

✅ Nitrogen (N), Phosphorus (P), Potassium (K)
✅ Temperature, Humidity, pH, Rainfall
✅ Target variable: Recommended Crop 🌾

<br><br>

🌱 Fertilizer Recommendation

The fertilizer recommendation system uses the following inputs:

✅ Temperature, Humidity, Moisture
✅ Soil Type, Crop Type
✅ Nitrogen (N), Potassium (K), Phosphorus (P)

🔹 Example Output:

Recommended Fertilizer → 17-17-17

<br><br>

🚀 Key Features

✔ Crop recommendation based on soil & climate data.

✔ Fertilizer recommendation based on soil, crop, nutrient, and environmental conditions.

✔ Machine Learning-driven decision-making for agricultural recommendations.

✔ User-friendly implementation with clear inputs & outputs.

<br><br>

🎯 Results & Performance

- Trained a Decision Tree Classifier on agricultural data.
- Model tested on unseen data to evaluate its prediction performance.
- Feature scaling (MinMaxScaler) used if implemented in the model.

<br><br>

📌 Conclusion

✅ Crop and fertilizer recommendations help demonstrate data-driven agricultural decision-making.

✅ Analyzes key factors like soil nutrients, weather conditions, and pH levels.

✅ Demonstrates the application of Machine Learning in agriculture.

<br><br>

🏆 Future Scope

🔹 Integration with IoT devices for real-time soil monitoring.

🔹 Mobile app implementation for easier access to recommendations.

🔹 Enhanced ML models for improved crop and fertilizer prediction.

---

🚀 Contribute, fork, and star the repository if you find it useful! ⭐
