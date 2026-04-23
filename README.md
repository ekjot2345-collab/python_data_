📊Gen AI Usage Data Analysis



🔍Overview



This project analyzes how Generative AI usage relates to student learning behavior and academic performance. The dataset contains student-level information such as study habits, AI usage patterns, attendance, concept understanding, and final academic outcomes.
The goal of this analysis is to explore whether the use of Gen AI tools has any measurable relationship with:
•	student performance
•	study efficiency
•	academic consistency
•	AI dependency
•	pass/fail outcomes



📁Dataset



The dataset used in this project is:
•	ai_impact_student_performance_dataset.csv
It includes variables such as:
•	uses_ai
•	ai_usage_time_minutes
•	ai_tools_used
•	ai_usage_purpose
•	ai_dependency_score
•	study_hours_per_day
•	attendance_percentage
•	concept_understanding_score
•	final_score
•	passed





🎯Objectives




The analysis focuses on the following questions:
1.	How many students use Generative AI?
2.	Which AI tools and purposes are most common?
3.	Does AI usage affect final academic performance?
4.	Is higher AI dependency linked to weaker outcomes?
5.	How do study hours, attendance, and understanding relate to final scores?
6.	Can student performance or pass/fail status be predicted using available features?


🛠️ Tools and Libraries


The analysis is performed in Python using:
•	pandas for data loading and manipulation
•	numpy for numerical calculations
•	matplotlib for visualizations
•	scikit-learn for model building and evaluation


⚙️ Analysis Steps



The project includes the following stages:
1.	Data loading and structure inspection
2.	Missing value checking and basic cleaning
3.	Filtering and sorting student records
4.	Grouped analysis of AI usage and academic outcomes
5.	Feature engineering such as study efficiency and risk flags
6.	Visual analysis using charts
7.	Predictive modeling using regression and classification
8.	Evaluation using suitable metrics



Evaluation Metrics





Two types of predictive tasks are relevant in this project:



1. Regression


Used when predicting final_score.
Common metrics:
•	MSE (Mean Squared Error)
•	RMSE (Root Mean Squared Error)
•	MAE (Mean Absolute Error)
•	R² Score


3. Classification






8. Used when predicting passed.
Common metrics:
•	Accuracy
•	Precision
•	Recall
•	F1-score
•	Confusion Matrix






Key Insights to Explore




Some useful insights from this dataset may include:
•	comparison of academic scores between AI users and non-users
•	most frequently used Gen AI tools
•	relationship between AI dependency and final performance
•	impact of study time on academic results
•	distribution of pass/fail outcomes across student groups




Example Visualizations




This project can include visualizations such as:
•	histogram of final scores
•	bar chart of AI usage purpose
•	scatter plot of study hours vs final score
•	box plot of final score by AI usage
•	confusion matrix for pass/fail prediction




Project Structure


Suggested project files:
•	README.md
•	ai_impact_student_performance_dataset.csv
•	student_performance_analysis_snippets.py



How to Run



1.	Make sure Python is installed.
2.	Install the required libraries:
pip install pandas numpy matplotlib scikit-learn
3.	Run the analysis script:
python student_performance_analysis_snippets.py


Conclusion




This project provides a practical analysis of how Generative AI usage may influence student study behavior and academic performance. It combines exploratory data analysis, visualization, feature engineering, and predictive modeling to generate meaningful insights from educational data.

