**📊 Logistic Regression – From Scratch (Binary Classification)**
This project implements Logistic Regression entirely from scratch in Python — without using any machine learning libraries — to perform binary classification tasks.

**📌 Key Features**
**📝 Pure Python Implementation** – No ML libraries like scikit-learn or numpy for training.

**🔄 Gradient Descent Optimization** – Manually updates model parameters to minimize loss.

**📈 Sigmoid Activation Function** – Converts linear outputs into probabilities between 0 and 1.

**🎯 Binary Classification** – Ideal for yes/no, pass/fail, or other two-class problems.

**📚 Educational Focus** – Perfect for learning the fundamentals of logistic regression step-by-step.

**🛠 Methodology**
**Data Input** – Load dataset with binary labels (e.g., pass/fail, spam/not spam).

**Data Preprocessing** – Manual scaling and normalization (if needed).

**Hypothesis Function** – Implements the logistic regression equation:

𝑦
𝑝
𝑟
𝑒
𝑑
=
𝜎
(
𝑤
𝑥
+
𝑏
)
y 
pred
​
 =σ(wx+b)
Where:

𝜎
(
𝑧
)
=
1
1
+
𝑒
−
𝑧
σ(z)= 
1+e 
−z
 
1
​
 
**Loss Function – Binary Cross-Entropy (Log Loss):**

𝐽
(
𝑤
,
𝑏
)
=
−
1
𝑛
∑
[
𝑦
log
⁡
(
𝑦
𝑝
𝑟
𝑒
𝑑
)
+
(
1
−
𝑦
)
log
⁡
(
1
−
𝑦
𝑝
𝑟
𝑒
𝑑
)
]
J(w,b)=− 
n
1
​
 ∑[ylog(y 
pred
​
 )+(1−y)log(1−y 
pred
​
 )]
**Gradient Descent –** Manual computation of partial derivatives and parameter updates.

**Model Prediction –** Classifies output as 1 if probability ≥ 0.5, else 0.

**📂 Files in This Repository**
code.py – Main script implementing logistic regression from scratch.

**student_performance.csv** – Example dataset for binary classification.

**README.md** – Detailed documentation (this file).

**🎯 Why This Project?**
Logistic Regression is one of the most fundamental algorithms in machine learning. By building it entirely from scratch, you’ll deeply understand how the math translates into code — from the sigmoid curve to parameter tuning via gradient descent.
