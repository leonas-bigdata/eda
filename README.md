# 📊 EDA & Benchmark Dataset Evaluation Repository

This repository module provides a pipeline for proccessing, exploratory data analysis and statical evaluation of four widely benchmark datasets of recommendation system, along-side our self-crawled dataset

The main purpose of this repo is to ensure fair, consistent, and reproducible evaluation across datasets before running recommendation experiments for  LightGCN, UltraGCN and LayerGCN.

# 🎯 Objectives

+ Standardize preprocessing for all datasets

+ Perform deep exploratory data analysis (EDA)

+ Compare statistical properties across datasets

+ Detect sparsity, bias, and structural differences

+ Ensure experimental fairness before model evaluation

+ Provide clean, ready-to-use interaction files for training

# 🧩 Benchmarked Datasets

The following four public benchmarks are analyzed and evaluated: Yelp2018, Gowalla, AmazonBook, MovieLens 1M

# 🔗 Data Sources (Reczoo m1 format)

The data source we will be using is from RecZoo: https://huggingface.co/reczoo

+ Yelp2018: https://huggingface.co/datasets/reczoo/Yelp18_m1

+ Gowalla: https://huggingface.co/datasets/reczoo/Gowalla_m1

+ AmazonBook: https://huggingface.co/datasets/reczoo/AmazonBooks_m1

+ MovieLens1M: https://huggingface.co/datasets/reczoo/Movielens1M_m1

# 🧪 Self-Crawled Dataset

This dataset was independently collected by our team to complement the four public benchmarks and to evaluate how recommendation models behave on realistic, noisy, and large-scale interaction data outside of curated academic datasets, with more than 1 million interactions and over 6000 users.