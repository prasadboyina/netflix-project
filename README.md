# netflix-project
🎬 Netflix Recommendation Engine
📌 Overview

This project builds a collaborative filtering-based recommendation system to suggest personalized movies to users based on their historical ratings.

The system leverages matrix factorization (SVD) to uncover hidden user preferences and deliver accurate recommendations at scale.

🚀 Key Highlights
Built on 24M+ ratings dataset
Processed 4,499 movies & 475K+ users
Reduced noise using data filtering techniques
Achieved RMSE ≈ 1.02 with cross-validation
Scalable and production-oriented pipeline
🧠 Problem Statement

Traditional recommendation systems struggle with:

Sparse user-item matrices
Cold-start problems
Noisy and low-engagement data

This project addresses these challenges using data preprocessing + matrix factorization techniques.

🏗️ Architecture / Workflow
Data Collection
Data Cleaning & Filtering
Exploratory Data Analysis (EDA)
User-Item Matrix Creation
Model Training (SVD)
Evaluation (RMSE)
Recommendation Generation
📊 Data Preprocessing
Removed users with < 36 ratings
Removed movies with < 908 ratings
Reduced dataset to high-quality interactions (~19.6M records)
Handled sparsity efficiently
⚙️ Tech Stack

Languages

Python

Libraries

Pandas
NumPy
Matplotlib
Seaborn
Scikit-Surprise

Algorithms

Singular Value Decomposition (SVD)
📈 Model Performance
Evaluation Metric: RMSE
Cross Validation: 3-Fold
Final Score: ~1.02 RMSE

👉 Indicates stable and reliable predictions across unseen data.

🎯 Features
Personalized movie recommendations
Scalable filtering mechanism
Robust evaluation pipeline
Clean and modular code structure
📂 Project Structure
Netflix-Recommendation/
│── data/
│── notebooks/
│── src/
│── models/
│── results/
│── README.md
