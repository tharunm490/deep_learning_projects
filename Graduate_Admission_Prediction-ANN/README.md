# Graduate Admission Prediction using ANN

This project predicts the **probability of admission to a Master's program** using an **Artificial Neural Network (ANN)** built with **Keras and TensorFlow**.

The problem is modeled as a **regression task**, where the output is the **chance of admit**, a continuous value between **0 and 1**.

---

## 📌 Project Overview

Graduate admission decisions depend on multiple academic and profile-based factors such as test scores, GPA, university reputation, and research experience.

In this project, an ANN is trained to learn the relationship between these factors and the **likelihood of admission**, helping to understand how different parameters influence admission outcomes.

---

## 🛠️ Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Pandas
- Scikit-learn
- Matplotlib

---

## 📂 Dataset Description

The dataset contains parameters that are commonly considered during **Master’s program admissions**.

### Input Features:

- **GRE Score** (out of 340)  
  Measures quantitative, verbal, and analytical skills.

- **TOEFL Score** (out of 120)  
  Indicates English language proficiency.

- **University Rating** (1 to 5)  
  Represents the reputation of the university.

- **Statement of Purpose (SOP)** (1 to 5)  
  Strength of the applicant’s statement.

- **Letter of Recommendation (LOR)** (1 to 5)  
  Strength of academic recommendations.

- **Undergraduate GPA** (out of 10)  
  Academic performance in undergraduate studies.

- **Research Experience** (0 or 1)  
  Indicates whether the applicant has research experience.

### Target Variable:

- **Chance of Admit** (0 to 1)  
  Represents the probability of getting admitted to a Master's program.

---

## 🔄 Workflow

1. Load and explore the dataset
2. Data preprocessing and normalization
3. Train-validation split
4. Build ANN model
5. Train the model using regression loss
6. Evaluate performance on validation data
7. Analyze loss vs epochs

---

## 🧠 Model Architecture

- **Input Layer:** All admission-related features
- **Hidden Layers:**
  - Two fully connected Dense layers
  - ReLU activation
- **Output Layer:**
  - Single neuron
  - Linear activation (regression)

---

## 📊 Results & Observations

- Training loss and validation loss converge closely
- Indicates **good generalization** and **no overfitting**
- Model learns relationships between academic factors and admission probability effectively

---

## 📖 Learning Outcome

- Implemented ANN for **regression problems**
- Understood feature influence on admission prediction
- Gained experience with:
  - Loss vs validation loss analysis
  - Early stopping concepts
  - ANN design for continuous outputs

---

## 👨‍💻 Author

**Tharun M**  
Deep Learning Learner | Machine Learning Enthusiast

---

## ⭐ Note

This is a **small, learning-focused project** created to strengthen understanding of ANN-based regression using real-world admission data.
