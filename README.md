# Titanic Data Analysis & Machine Learning Project

This project is a beginner-friendly exploration of the **Titanic dataset**.  
Using *Python, Pandas, NumPy, Matplotlib, and Scikit-Learn*, the project both visualizes important insights about passengers and builds a machine learning model to predict survival.

<img width="1915" height="1004" alt="image" src="https://github.com/user-attachments/assets/41aa29a2-d684-471a-8fc9-303825b46dbb" />
<img width="782" height="338" alt="image" src="https://github.com/user-attachments/assets/a8619dcc-2d4e-4a67-8ca8-75d43914effd" />

---

## 🔹 Project Goals

1. **Data Analysis & Visualization**  
   - Practice data cleaning and exploratory analysis  
   - Understand passenger demographics and survival trends  

2. **Machine Learning**  
   - Train a **Logistic Regression** model to predict survival  
   - Evaluate the model using accuracy and cross-validation  

---

## 📊 Visualizations Included

### 1. **Passenger Class Distribution**
Bar chart showing how many passengers belonged to 1st, 2nd, and 3rd class.

### 2. **Age Group Distribution**
Pie chart separating passengers into:
- Kids (under 14)
- Teenagers (14–17)
- Adults (18–60)
- Elderly (60+)

### 3. **Survival vs. Death**
Bar chart showing total survivors vs. total deaths.

### 4. **Fare Distribution**
Histogram illustrating passenger fare distribution.

### 5. **Survivors by Gender**
Bar chart comparing male vs. female survival counts.

### 6. **Survival Rate by Class**
Bar chart showing the survival percentage for each passenger class.

---

## 🤖 Machine Learning Model

- **Model Used:** Logistic Regression  
- **Feature Scaling:** StandardScaler (to normalize numeric features)  
- **Performance:**
  - Test set accuracy: ~80%  
  - Cross-validation scores: ~78% mean  
- **Features Used:** `pclass`, `sex`, `age`, `fare`, `sibsp`, `parch`, `family_size`, `is_alone`  

---

## 🛠️ Technologies Used

- **Python 3**
- **Pandas** — data manipulation  
- **NumPy** — numerical computations  
- **Matplotlib** — data visualization  
- **Scikit-Learn** — machine learning  

---

## 📁 Dataset

The project uses the classic **Titanic dataset**, containing features such as:

- `pclass`
- `survived`
- `sex`
- `age`
- `fare`
- `sibsp`
- `parch`
- `family_size`
- `is_alone`

Make sure that the file `titanic.csv` is located in the same directory as the scripts.

