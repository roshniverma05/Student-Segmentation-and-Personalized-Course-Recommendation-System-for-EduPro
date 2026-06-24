# Student Segmentation and Personalized Course Recommendation System for EduPro

![React](https://img.shields.io/badge/React-Frontend-blue)
![Vite](https://img.shields.io/badge/Vite-Build-purple)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-KMeans-green)
![Status](https://img.shields.io/badge/Status-Completed-success)

## Overview

The **Student Segmentation and Personalized Course Recommendation System for EduPro** is a data-driven learning analytics platform developed to understand learner behavior, identify distinct learner segments, and provide personalized course recommendations.

The project combines educational data analytics, machine learning, and interactive visualizations to support adaptive learning experiences and improve learner engagement.

---

## Problem Statement

Online learners exhibit diverse learning behaviors and preferences:

* Some explore beginner-level courses across multiple domains.
* Some specialize deeply within a specific subject area.
* Others focus on career-oriented certifications and professional growth.

Traditional recommendation systems often fail to account for these differences, resulting in generic recommendations and reduced learner engagement.

EduPro required a personalized learning intelligence system capable of:

* Understanding learner behavior patterns
* Segmenting learners into meaningful groups
* Providing personalized course recommendations
* Supporting long-term learner engagement

---

## Project Objectives

* Analyze learner behavior using educational transaction data
* Build learner-level analytical profiles
* Segment learners using machine learning techniques
* Generate personalized course recommendations
* Develop an interactive learning analytics dashboard
* Improve learner engagement and retention

---

## Dataset Description

The project utilizes three integrated datasets.

### Users Dataset

| Attribute | Description               |
| --------- | ------------------------- |
| UserID    | Unique learner identifier |
| Age       | Learner age               |
| Gender    | Learner gender            |

### Courses Dataset

| Attribute      | Description                      |
| -------------- | -------------------------------- |
| CourseID       | Unique course identifier         |
| CourseCategory | Course domain/category           |
| CourseType     | Course format                    |
| CourseLevel    | Beginner, Intermediate, Advanced |
| CourseRating   | Learner rating                   |

### Transactions Dataset

| Attribute       | Description            |
| --------------- | ---------------------- |
| UserID          | Learner identifier     |
| CourseID        | Course identifier      |
| TransactionDate | Enrollment date        |
| Amount          | Course purchase amount |

---

## Feature Engineering

### Engagement Features

* Total Courses Enrolled
* Average Courses per Category
* Enrollment Frequency

### Preference Features

* Preferred Course Category
* Preferred Course Level
* Average Course Rating Enrolled

### Behavioral Features

* Average Spending per Learner
* Diversity Score
* Learning Depth Index

---

## Methodology

### 1. Learner Profile Construction

Learner profiles were created by aggregating demographic, course, and transaction data at the learner level.

### 2. Data Preprocessing

* Missing Value Handling
* Feature Scaling
* Normalization
* Categorical Encoding
* Noise Reduction

### 3. Learner Segmentation

Machine learning techniques applied:

* K-Means Clustering
* Elbow Method
* Silhouette Analysis

### 4. Personalized Recommendation System

Recommendations were generated using:

* Content-Based Filtering
* Similar Learner Profiles
* Cluster Popularity Analysis
* Rating-Weighted Relevance

---

## Dashboard Features

### Analytics Dashboard

* Learner Segmentation Overview
* Cluster Distribution Analysis
* Enrollment Analytics
* Category Insights
* Spending Analysis
* Recommendation Insights

### Interactive Visualizations

* KPI Cards
* Pie Charts
* Bar Charts
* Radar Charts
* Scatter Plots
* Segment Comparison Panels

---

## Technologies Used

### Frontend

* React.js
* JavaScript (ES6+)
* Vite
* Recharts

### Machine Learning & Analytics

* K-Means Clustering
* Learning Analytics
* Educational Data Mining

### Development Tools

* Git
* GitHub
* Vercel

---

## Results and Insights

The learner segmentation process identified distinct learner groups:

### Exploratory Learners

* High diversity score
* Broad category exploration
* Multi-domain interests

### Specialized Learners

* Deep engagement within a specific subject
* Advanced course participation

### Career-Oriented Learners

* Certification-focused behavior
* High spending patterns
* Professional development goals

### Casual Learners

* Limited engagement
* Low enrollment frequency

The segmentation framework enabled more targeted recommendations and improved learner understanding.

---

## Project Deliverables

* Research Paper
* Interactive Learning Analytics Dashboard
* Learner Segmentation Framework
* Personalized Recommendation Engine
* Executive Summary

---

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Student-Segmentation-and-Personalized-Course-Recommendation-System-for-EduPro.git
```

Navigate to the project directory:

```bash
cd Student-Segmentation-and-Personalized-Course-Recommendation-System-for-EduPro
```

Install dependencies:

```bash
npm install
```

Run the application:

```bash
npm run dev
```

---

## Deployment

Live Project:

Add your Vercel deployment URL here.

Example:

```text
https://student-segmentation-and-personaliz.vercel.app/
```

---

## Future Scope

* Real-Time Recommendation Systems
* Deep Learning-Based Recommendations
* Adaptive Learning Paths
* Predictive Learner Analytics
* AI-Powered Learning Assistants

---

## Developed By

**Roshni Verma**

B.Tech – Information Technology

Internship Project

Unified Mentor

2025 – 2026

---

## License

This project was developed for educational, research, and internship purposes.
