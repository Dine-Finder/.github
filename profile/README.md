<div align="center">
    <img src="./images/logo.png" alt="logo" width="150">
</div>

# Dine Finder - A Restaurant Recommendation System Web App

## GitHub Badges

| Backend | Frontend |
| --- | --- |
| ![GitHub issues](https://img.shields.io/github/issues/Dine-Finder/Backend) | ![GitHub issues](https://img.shields.io/github/issues/Dine-Finder/Frontend) |
| ![GitHub forks](https://img.shields.io/github/forks/Dine-Finder/Backend) | ![GitHub forks](https://img.shields.io/github/forks/Dine-Finder/Frontend) |
| ![GitHub stars](https://img.shields.io/github/stars/Dine-Finder/Backend) | ![GitHub stars](https://img.shields.io/github/stars/Dine-Finder/Frontend) |
| ![GitHub license](https://img.shields.io/github/license/Dine-Finder/Backend) | ![GitHub license](https://img.shields.io/github/license/Dine-Finder/Frontend) |

## Commit History

| Backend | Frontend |
| --- | --- |
| ![GitHub commit activity](https://img.shields.io/github/commit-activity/m/Dine-Finder/Backend) | ![GitHub commit activity](https://img.shields.io/github/commit-activity/m/Dine-Finder/Frontend) |
| ![GitHub last commit](https://img.shields.io/github/last-commit/Dine-Finder/Backend) | ![GitHub last commit](https://img.shields.io/github/last-commit/Dine-Finder/Frontend) |

# DineFinder 

DineFinder is a restaurant recommendation system designed to help you find the best dining spots in Manhattan, New York City. Leveraging historical taxi trip data, advanced machine learning techniques, and real-time busyness predictions, DineFinder ensures you can avoid crowded restaurants and have a delightful dining experience.

## Table of Contents
- [DineFinder](#dinefinder)
  - [Table of Contents](#table-of-contents)
  - [Tech Stack Badges](#tech-stack-badges)
  - [Introduction](#introduction)
  - [Features](#features)
  - [Gallery](#gallery)
    - [Mobile View](#mobile-view)
    - [Desktop View](#desktop-view)
  - [What Makes Us Unique](#what-makes-us-unique)
  - [Technologies Used](#technologies-used)
  - [Working Videos](#working-videos)
    - [Mobile Working Video](#mobile-working-video)
    - [Desktop Working Video](#desktop-working-video)


## Tech Stack Badges 

![Python](https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Material UI](https://img.shields.io/badge/Material--UI-0081CB?style=for-the-badge&logo=material-ui&logoColor=white)
![Chakra UI](https://img.shields.io/badge/Chakra--UI-319795?style=for-the-badge&logo=chakra-ui&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-00000F?style=for-the-badge&logo=mysql&logoColor=white)
![Numpy](https://img.shields.io/badge/Numpy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Scipy](https://img.shields.io/badge/SciPy-8CAAE6?style=for-the-badge&logo=scipy&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Google](https://img.shields.io/badge/Google-4285F4?style=for-the-badge&logo=google&logoColor=white)
![BERT](https://img.shields.io/badge/BERT-4285F4?style=for-the-badge&logo=bert&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD400?style=for-the-badge&logo=hugging-face&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-9C3D3D?style=for-the-badge&logo=sqlalchemy&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![npm](https://img.shields.io/badge/npm-CB3837?style=for-the-badge&logo=npm&logoColor=white)
![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)
![AWS EC2](https://img.shields.io/badge/AWS_EC2-FF9900?style=for-the-badge&logo=amazon-ec2&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)
![NGINX](https://img.shields.io/badge/NGINX-009639?style=for-the-badge&logo=nginx&logoColor=white)
![Gunicorn](https://img.shields.io/badge/Gunicorn-499848?style=for-the-badge&logo=gunicorn&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white)


## Introduction
Manhattan is known for its diverse culinary scene, but choosing the right restaurant can be overwhelming. DineFinder simplifies this process by providing real-time restaurant busyness predictions and personalized recommendations based on user preferences and sentiment analysis of reviews. Whether you're a local or a visitor, DineFinder enhances your dining experience by guiding you to the best times and locations for your meals.

## Features
- **Real-Time Busyness Predictions**: Avoid crowded restaurants with up-to-date occupancy data.
- **Personalized Recommendations**: Get suggestions tailored to your tastes based on review sentiment analysis.
- **Tag-Based Search**: Use tags generated from reviews to find restaurants matching your specific preferences.
- **Interactive Maps**: Visualize restaurant locations and busyness levels on dynamic maps.
- **Sentiment Analysis**: Understand the overall sentiment towards restaurants from aggregated review data.

## Gallery

### Mobile View 
<div align="center">
    <img src="./images/mobile1.jpg" alt="Mobile View 1" width="200">
    <img src="./images/mobile2.jpg" alt="Mobile View 2" width="200">
    <img src="./images/mobile3.jpg" alt="Mobile View 3" width="200">
    <img src="./images/mobile4.jpg" alt="Mobile View 4" width="200">
</div>

### Desktop View 
<div align="center">
    <img src="./images/desktop1.png" alt="Desktop View 1" width="400">
    <img src="./images/desktop2.png" alt="Desktop View 2" width="400">
    <img src="./images/desktop3.png" alt="Desktop View 3" width="400">
</div>

## What Makes Us Unique
- **Historical Taxi Data**: Utilizes taxi trip data to predict restaurant busyness.
- **Advanced ML Models**: Combines Google BERT for NLP tasks and XGBoost for predictive modeling.
- **User-Centric Design**: Focuses on enhancing user experience with a friendly interface and intuitive navigation.
- **Comprehensive Dataset**: Integrates various data sources to provide accurate and reliable recommendations.

## Technologies Used
- **Backend**: Flask, Gunicorn, NGINX
- **Frontend**: React, Vite, Tailwind CSS, Leaflet, Chart.js, Material UI
- **Database**: MySQL, SQLAlchemy
- **Machine Learning**: Google BERT, XGBoost
- **CI/CD**: GitHub Actions, Docker

## Working Videos

### Mobile Working Video 

<div align="center">
  <video width="400" controls autoplay muted>
    <source src="./videos/mobile.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>
</div>

### Desktop Working Video 
<div align="center">
  <video width="1000" controls autoplay muted>
    <source src="./videos/desktop2.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>
</div>

---

Made with ❤️ by Group 10: Mohammed Musaddique, Haoyu Zheng, Barry Carmody, Bhargav Nikumbh
