# 📊 EDA & Benchmark Dataset Evaluation RepositoryThis repository is used for preprocessing, analyse the 4 benchmakr data and a self-crawled data.

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

All datasets follow the Reczoo .inter format, making them consistent for preprocessing and evaluation.