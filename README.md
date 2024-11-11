# 🚗 Autonomous Driving Decision Support System using LIME

This project focuses on using **LIME (Local Interpretable Model-agnostic Explanations)** to create an explainable decision support system for autonomous driving models.
The goal is to make the decision-making process of autonomous vehicles more transparent and interpretable.

## 🌟 Features
- **Explainability**: Uses LIME to interpret the predictions of the autonomous driving model.
- **Transparency**: Provides insights into the decisions made by the model.

## 🛠️ Tech Stack
- **Python** (for ML model and LIME)
- **TensorFlow** / **Scikit-learn** (for machine learning)
- **LIME** (for model interpretability)

## 📊 Dataset

The dataset used in this study is sourced from two main datasets:

1. **nuScenes Dataset**:  
   - Contains **20,664 camera images**, **3,444 lidar sweeps**, **17,220 radar sweeps**, and detailed map information.  
   - Features full sensor suites including **1x LIDAR**, **5x RADAR**, **6x cameras**, **IMU**, **GPS**, and manual annotations for **23 object classes**.
   
2. **Oxford Radar RobotCar Dataset**:  
   - This dataset includes radar sensor data captured by a self-driving car platform navigating both **urban and rural environments**.  
   - It provides valuable insights into radar sensors for autonomous driving tasks such as **object detection**, **localization**, and **tracking**.


 ## 📈 Preliminary Results
The preliminary results demonstrate the effectiveness of the proposed Autonomous Driving Decision Support System (ADDSS) in providing interpretable explanations for autonomous driving decisions.

**Key Findings:**
- **LIME Analysis**: LIME analyses reveal important insights into the model's predictions, such as the influence of specific input features.
    - Pedestrian detection was found to contribute 40% of the braking decisions.
- **Accuracy of Decision Factors**: The system shows an 85% accuracy in identifying key features impacting the model's predictions during complex driving scenarios.
- **Convolutional Neural Network (CNN) Model**: The CNN model is effective in classifying images from the autonomous driving dataset. By utilizing LIME, we gained insights into the important regions of the input images that influence the model's predictions.


## 📑 Conclusion
In conclusion, this project focuses on developing an Autonomous Driving Decision Support System using machine learning techniques like CNN to classify images accurately. Leveraging LIME explanations has enabled us to gain valuable insights into the model’s decision-making process, specifically identifying important features and regions within the images that contribute to predictions.

**Key Takeaways:**
- **Interpretability in Autonomous Driving:** Interpretable machine learning models are crucial for safety-critical applications like autonomous driving. Understanding the factors influencing predictions enhances trust and transparency, which is vital for the deployment of reliable autonomous systems.
- **Future Improvements:** Future work will focus on refining the model architecture and training process to improve accuracy and interpretability. Additionally, exploring additional data sources and advanced algorithms will likely enhance performance and provide deeper insights.
