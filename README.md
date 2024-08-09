
---

# 🌟 AutoML Hierarchical Forecasting with Vertex AI 🌟

Welcome to the **AutoML Hierarchical Forecasting** project! This repository houses a comprehensive journey from data exploration to model deployment, using Google Cloud's Vertex AI to harness the power of machine learning. Whether you're a data enthusiast or a seasoned data scientist, this project provides valuable insights into building and deploying forecasting models at scale.

## 🗂️ Project Structure

```plaintext
lhl-final-project/
│
├── data/
│   ├── raw/                      # Raw synthetic sales data
│   │   └── synthetic_sales_data.csv
│   ├── test/                     # Test dataset for model evaluation
│   │   └── sales_forecasting_test.csv
│   └── train/                    # Training dataset for model building
│       └── sales_forecasting_train.csv
│
├── images/                       # Visuals and plots generated during the project
│   ├── batch_prediction_screenshot.png
│   ├── prediction_vs_ground_truth.png
│   ├── rel_plot.png
│   └── upload_train_data_gcs.png
│
├── notebooks/                    # Jupyter notebooks guiding each project stage
│   ├── EDA.ipynb                 # Exploratory Data Analysis
│   ├── GoogleCloudEnvSetup.ipynb # Google Cloud environment setup
│   ├── model_development_and_prediction.ipynb  # Model development and deployment
│   └── results_dataset.ipynb     # Prediction results analysis
│
├── dataset.csv                   # Consolidated dataset for final analysis
└── README.md                     # You're reading it right now!
```

## 🎯 Project Objectives

This project aims to accomplish the following key tasks:

1. **Data Preparation**:
   - Transform synthetic sales data into a format suitable for hierarchical forecasting.
   
2. **Exploratory Data Analysis (EDA)**:
   - Dive deep into the data to identify patterns, trends, and anomalies that will inform the model-building process.
   
3. **Model Development**:
   - Leverage Vertex AI AutoML to construct a robust hierarchical forecasting model.
   - Train the model on curated sales data to predict future trends with precision.
   
4. **Deployment and Batch Prediction**:
   - Seamlessly deploy the trained model using the Vertex AI SDK for Python.
   - Perform batch predictions on new data and assess the model's performance.

5. **Results Analysis**:
   - Visualize and evaluate the model's predictions to ensure accuracy and reliability.

## 🚀 Getting Started

### Prerequisites

Before diving in, ensure you have the following:

- Python 3.7+
- Google Cloud SDK
- Vertex AI SDK for Python
- Jupyter Notebook

### Setup Instructions

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/lhl-final-project.git
   cd lhl-final-project
   ```

2. **Google Cloud Setup**:
   - Follow the step-by-step instructions in `GoogleCloudEnvSetup.ipynb` to authenticate your environment and enable the necessary APIs.

3. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Notebooks**:
   - Begin with `EDA.ipynb` to explore the data.
   - Proceed to `model_development_and_prediction.ipynb` for model building and deployment.
   - Finish with `results_dataset.ipynb` to analyze the forecasted results.

## 📊 Results & Insights

Explore the `images/` directory to find visual representations of the model's performance. Detailed analyses and evaluation metrics are documented in the `results_dataset.ipynb` notebook. Key highlights include:

- **Prediction vs. Ground Truth**: See how the model's forecasts align with actual data.
- **Batch Predictions**: Visual snapshots of the batch prediction process, showcasing the model's scalability.

## 🤝 Contributing

We welcome contributions! If you have suggestions or improvements, feel free to open an issue or submit a pull request. Let's build something great together.

## 📜 License

This project is licensed under the MIT License. For more information, see the `LICENSE` file.

---

Thank you for exploring this project. We hope it serves as a valuable resource on your machine learning journey. Happy forecasting! 📈

---

