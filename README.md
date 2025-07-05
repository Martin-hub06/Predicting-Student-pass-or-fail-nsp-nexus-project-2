# Predicting-Student-pass-or-fail-nsp-nexus-project-2
📊 Student Performance Prediction using Logistic Regression

This project demonstrates how to use a Logistic Regression model to predict whether a student will PASS or FAIL based on two simple but important features:

📚 Hours Studied

🏫 Attendance Percentage



---

🧠 Objective

To build a machine learning model that accurately predicts student outcomes using logistic regression, enabling basic academic performance forecasting based on study habits and attendance.


---

📁 Dataset

A manually created dataset with 10 records (can be extended to 20+) having the following fields:

Hours_Studied – Number of hours the student studied

Attendance – Attendance percentage

Pass_Fail – Target output (1 = Pass, 0 = Fail)



---

🔧 Tools & Libraries Used

Python 3.x

Pandas

Matplotlib & Seaborn

scikit-learn

Jupyter Notebook / Google Colab



---

🔍 Steps Followed

1. ✅ Created a custom dataset inside the notebook.


2. 📊 Visualized data using scatter plots and heatmaps.


3. ✂ Split data into training and testing sets using train_test_split.


4. 🧠 Trained a Logistic Regression model using scikit-learn.


5. 📈 Evaluated the model using:

Accuracy Score

Confusion Matrix

Classification Report



6. 👤 Accepted user input for real-time prediction of a student's result.




---

💻 User Input Feature

At the end of the notebook, the user is prompted to enter:

✏ Hours Studied

🧮 Attendance Percentage


The model then prints one of the following results:

✅ The student is likely to PASS.

❌ The student is likely to FAIL.


This feature makes the notebook interactive and user-friendly!


---

📈 Sample Output

Enter Hours Studied: 5  
Enter Attendance (%): 80

🔍 Prediction Result:
✅ The student is likely to PASS.


---

💡 How to Run

1. Download or clone the notebook file.


2. Open Student_Pass_Prediction_Logistic_Regression.ipynb in Jupyter Notebook or Google Colab.


3. Run all cells sequentially.


4. Enter your own values for hours studied and attendance when prompted.




---

📌 Project Status

✅ Basic implementation is complete.

🔄 Can be extended by:

Adding more real-world data

Including new features like test scores, assignments, etc.

Using more advanced classifiers (Random Forest, SVM, etc.)




---

🧑‍💻 Author

Marten Jothi Victor
📧 mjv3140@gmail.com
🎓 Intern at NSP NEXUS – Week 2 Project


---

📎 License

This project is released under the MIT License and intended for educational purposes.
