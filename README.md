# Hybrid AI Tutor Recommendation System

This project implements a Hybrid AI-based Tutor Recommendation System 
designed for personalized and fair tutor-student matching in the Saudi educational context.

## Features

- Content-based soft rule filtering
- Matrix Factorization (SVD) using Surprise
- Hybrid weighted scoring
- Precision@K, Recall@K, NDCG@K evaluation
- Popularity-bias fairness analysis
- Curriculum feature reduction (19 → 5 groups)
- Gradio UI prototype

## Project Structure

- data/ → Student, Tutor, Curriculum, and Interaction datasets
- src/ → Main recommendation system implementation
- requirements.txt → Required dependencies

## Methodology

1. Data Cleaning & Standardization
2. Curriculum Group Feature Reduction
3. Soft Rule-Based Matching
4. Collaborative Filtering (SVD)
5. Hybrid Score Combination
6. Fairness & Ranking Evaluation

## Final Performance (Strict Evaluation)

- Precision@5: 0.8920
- Recall@5: 0.9957
- NDCG@5: 0.9538
- Catalog Coverage: 85.35%
- Exposure to Less Popular Tutors: 63.84%

## Authors

Mashael Saeed, Sarah Elshiaty, Seifeldin Elshiaty

Effat University  
Computer Science Department  
Saudi Arabia
