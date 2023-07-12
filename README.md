# Decoding Titanic: Predicting Survival 🚢⚓

## Table of Contents
1. [Introduction](#Introduction)
2. [Dataset](#Dataset)
3. [Exploratory Data Analysis](#Exploratory-Data-Analysis)
4. [Data Cleaning & Feature Engineering](#Data-Cleaning-&-Feature-Engineering)
5. [Data Split: Train, Validation, Test](#Data-Split)
6. [Model Selection](#Model-Selection)
7. [Hyperparameter Tuning](#Hyperparameter-Tuning)
8. [Ensemble Techniques](#Ensemble-Techniques)
9. [Model Evaluation](#Model-Evaluation)
10. [Model Interpretation and Insights](#Model-Interpretation-and-Insights)
11. [Conclusion](#Conclusion)

<a name="Introduction"></a>
## 1. Introduction 🌟
This repository contains a comprehensive step-by-step guide to the classic machine learning project, predicting the survivors of the Titanic disaster. The project includes everything from data cleaning, exploratory data analysis (EDA), model selection, hyperparameter tuning, to model interpretation. Here, I will present the code, the reasons behind the choices I made, and the final results.

<a name="Dataset"></a>
## 2. Dataset 📁
The dataset I used is the Titanic dataset from the Kaggle competition. It contains demographics and passenger information from 891 of the 2224 passengers and crew on board the Titanic. You can access this dataset from the [Kaggle Titanic competition page](https://www.kaggle.com/competitions/titanic/data) or import it directly via seaborn.

<a name="Exploratory-Data-Analysis"></a>
## 3. Exploratory Data Analysis 📊
Exploratory data analysis helped us understand the data structure, find patterns, spot anomalies, and test hypotheses with the help of summary statistics and graphical representations.

<a name="Data-Cleaning-&-Feature-Engineering"></a>
## 4. Data Cleaning & Feature Engineering ⚙️
I carefully dealt with missing values and outliers to ensure the data's integrity and usability. Several features were engineered to best represent the existing information and create a better perspective of passengers' survival possibilities.

<a name="Data-Split"></a>
## 5. Data Split: Train, Validation, Test 🧪
The data was split into training, validation, and test sets to build and test our model's generalization ability, following a 70-15-15 split proportion.

<a name="Model-Selection"></a>
## 6. Model Selection 🤖
The top models evaluated for the task were Support Vector Classifier (SVC), Logistic Regression, RandomForestClassifier, and K-Nearest Neighbors (KNN). These models were selected considering their strengths, data characteristics, and the nature of the problem.

<a name="Hyperparameter-Tuning"></a>
## 7. Hyperparameter Tuning 🔧
For optimal performance, model parameters were fine-tuned using techniques like grid search. This iterative step ensured satisfactory model performance.

<a name="Ensemble-Techniques"></a>
## 8. Ensemble Techniques 🪁
Two ensemble methods, Voting Classifier and Stacking Classifier, were employed to integrate multiple models' predictions, often outperforming any single model's performance.

<a name="Model-Evaluation"></a>
## 9. Model Evaluation 🎯
The performance of our chosen model, Logistic Regression, was evaluated using pre-determined metrics applied to our test set.

<a name="Model-Interpretation-and-Insights"></a>
## 10. Model Interpretation and Insights 💡
Through model interpretation, we gained a deeper understanding of the factors influencing the model's predictions, covering coefficient importance and permutation importance. 

<a name="Conclusion"></a>
## 11. Conclusion 🎉
Our detailed EDA revealed fascinating aspects of the Titanic disaster. With careful feature engineering and model selection, I achieved an accuracy of 83.5%—a significant improvement over the baseline. The process shed light on the human stories behind the data, enhancing our understanding of survival factors during the Titanic disaster.

## Getting Started 🏁
Please refer to the included Jupyter Notebook (`decoding_titanic_github_230711_ver3.ipynb`) for the full code, commentary, and results. The original data can be directly imported through seaborn or downloaded from the [Kaggle Titanic competition page](https://www.kaggle.com/competitions/titanic/data).

### Prerequisites 📋
To run this project, you'll need the following:
- Python 3.x
- Jupyter Notebook
- Libraries: NumPy, Pandas, Matplotlib, Seaborn, Scikit-Learn

### Installing 🛠️
1. Clone this repository.
2. Install the prerequisites.
3. Open the Jupyter Notebook.

Enjoy exploring, and don't hesitate to reach out if you have any questions or suggestions!

## Contributors ✨
I'd like to extend my heartfelt gratitude towards a few special individuals who have immensely contributed to my journey. I thank [Duck-m-a-n](https://github.com/Duck-m-a-n) for being a continuous source of inspiration. His incredible work ethic and growth mindset have not only motivated me, but have also shown me the possibilities of what relentless learning and persistence can achieve.

I also owe a huge thanks to [wagonpusher](https://github.com/wagonpusher) for being a pillar of mental support. His patience and willingness to listen to my trials and errors throughout the course of this project have made the process much smoother. Besides being an excellent listener, he's also a fantastic engineer, whose insightful feedback has been crucial to my learning.

Thank you both for your invaluable contribution to my growth and this project.

## License 📄
This project is licensed under the MIT License - see the [LICENSE.md](https://github.com/FutureGoose/decoding_titanic/blob/main/LICENSE) file for details.

## Acknowledgments 🙏
I want to thank the Kaggle community for making the Titanic dataset readily accessible and fostering a space for learning and growth.
