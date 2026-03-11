# Student Placement Prediction using Machine Learning

## Overview

This project predicts whether a student will be placed or not based on academic performance, skills, and extracurricular activities.
The model analyzes various student attributes such as CGPA, internships, projects, coding skills, aptitude scores, and communication skills to determine the likelihood of placement.

A Machine Learning model (Random Forest Classifier) is used to train the dataset and make predictions.

---

## Dataset Description

The dataset contains information about students and their academic, technical, and personal attributes.

### Main Features

* Age
* CGPA
* Internships Count
* Projects Count
* Certifications Count
* Coding Skill Score
* Aptitude Score
* Communication Skill Score
* Logical Reasoning Score
* Hackathons Participated
* GitHub Repositories
* LinkedIn Connections
* Mock Interview Score
* Attendance Percentage
* Backlogs
* Extracurricular Score
* Leadership Score
* Volunteer Experience
* Sleep Hours
* Study Hours per Day
* Gender
* Branch
* College Tier

### Target Variable

* **Placement Status**

  * 1 → Placed
  * 0 → Not Placed

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Jupyter Notebook / Kaggle Notebook

---

## Machine Learning Model

The project uses the **Random Forest Classifier**, an ensemble learning algorithm that builds multiple decision trees and combines their predictions to improve accuracy.

Advantages:

* Handles large datasets effectively
* Works well with numerical and categorical features
* Reduces overfitting compared to single decision trees

---

## Project Workflow

### 1. Data Collection

Load the dataset containing student academic and skill details.

### 2. Data Preprocessing

* Remove duplicates
* Handle missing values
* Convert categorical values into numerical format
* Apply one-hot encoding for categorical variables

### 3. Feature Selection

Remove unnecessary columns such as:

* student_id
* salary_package_lpa

### 4. Train-Test Split

The dataset is divided into:

* **80% Training Data**
* **20% Testing Data**

### 5. Model Training

Train the Random Forest model using the training dataset.

### 6. Prediction

Use the trained model to predict placement outcomes on the test dataset.

### 7. Model Evaluation

Model performance is evaluated using **Accuracy Score**.

---

## Example Output

Model Accuracy:

```
0.87
```

This means the model correctly predicts placement outcomes about **87% of the time**.

---

## Project Structure

```
Student-Placement-Prediction
│
├── dataset.csv
├── placement_prediction.ipynb
├── README.md
```

---

## Applications

* Helps colleges analyze placement readiness of students
* Assists training departments in identifying skill gaps
* Guides students on areas to improve for better placement chances

---

## Conclusion

This project demonstrates how machine learning can be used to analyze student performance data and predict placement outcomes. By analyzing various academic and skill-based attributes, the system provides insights that can help students and institutions improve employability.

---
