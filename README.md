# Project Overview

This repository contains the final project for the Ohio State University Computer Vision course, completed by my partner Rohit Anand and me. The project focuses on **lighting-invariant soybean disease detection** by comparing a custom **Mahalanobis distance-based classifier** with a **Random Forest classifier** under both normal and synthetically altered lighting conditions.

The goal was to demonstrate how classical image processing techniques such as background subtraction and shape descriptor extraction, when combined with basic machine learning algorithms, can be applied to solve real-world agricultural problems.

We used standard Python libraries including **scikit-image**, **scikit-learn**, and **OpenCV**, and achieved the following milestones:

 - Developed a feature extraction pipeline leveraging HSV color space, lesion count, area, and eccentricity, achieving **over 80% test accuracy** under normal lighting.

 - Implemented a custom **Mahalanobis distance classifier** (with no hyperparameter tuning needed) and benchmarked its performance against **Random Forest**, using **McNemar’s test** for statistical comparison.

 - Assessed lighting robustness via synthetic lighting perturbations and **PCA visualizations**, demonstrating improved class separability and reduced degradation for our custom features.

Note: This project involved limited use of AI-assisted tools (e.g., ChatGPT, GitHub Copilot) during development and report drafting.

Full project report available [here](./report/final_project_report.pdf)

---

# Directory Structure Overview

TODO