# CodTech_MovieRecommendation_Task4
# Recommendation System using Collaborative Filtering

## 📌 Project Overview
This project implements a **Personalized Recommendation Engine** using **Matrix Factorization**, a powerful Collaborative Filtering technique. Built as part of the **CODTECH IT SOLUTIONS** internship, the system predicts user preferences by analyzing historical rating patterns from the **MovieLens 100k** dataset.

The model goes beyond simple popularity-based suggestions by learning "latent factors" for both users and movies, allowing it to uncover hidden patterns in viewing behavior.

## 🚀 Key Features
* **Matrix Factorization Architecture:** Implements a neural network with Embedding layers to map users and items into a shared latent space.
* **Dot Product Similarity:** Computes the interaction between user preferences and movie characteristics to predict ratings.
* **Data Sparsity Management:** Successfully handles the "sparse matrix" challenge common in real-world recommendation data.
* **Evaluation Dashboard:** Includes a multi-pane visualization suite showing model convergence, rating distributions, and top-N recommendations.

## 🛠️ Tech Stack
* **Python** (Core Logic)
* **TensorFlow / Keras** (Deep Learning Framework)
* **Pandas & NumPy** (Data Engineering)
* **Seaborn & Matplotlib** (Advanced Data Visualization)

## 📋 Model Architecture & Logic
1.  **Input:** User IDs and Movie IDs are fed into separate input branches.
2.  **Embedding Layers:** These IDs are converted into 50-dimensional vectors (Latent Factors).
3.  **Dot Product:** The core "Collaborative Filtering" happens here, calculating the mathematical similarity between a user and a movie.
4.  **Optimization:** The model is trained using the **Adam Optimizer** and **Mean Squared Error (MSE)** loss function.

## 📊 Evaluation & Results
The deliverable includes a comprehensive analysis dashboard:
* **Sparsity Heatmap:** Visualizes the raw user-item interaction matrix.
* **Loss Curves:** Tracks the reduction of Mean Squared Error (MSE) over training epochs.
* **Top-N Predictions:** Showcases real-world results by generating a "Top 5" recommendation list for specific users.

## ⚙️ How to Use
1.  Install the required dependencies:
    ```bash
    pip install tensorflow pandas numpy seaborn matplotlib scikit-learn
    ```
2.  Run the notebook cells to download the MovieLens dataset and train the model.
3.  View the final dashboard to see personalized recommendations.

---
**Author:** Dhruti  
**Task:** 04 - Recommendation System  
**Organization:** CODTECH IT SOLUTIONS
