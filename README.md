# 🩺 Insurance Dataset Analysis: Effect of Sex on Charges

This project explores whether **sex (male/female)** has a significant impact on **insurance charges** using the popular *Insurance Dataset*.  
The analysis includes **data preprocessing, exploratory data analysis (EDA), simple linear regression, statistical testing (t-test), and visualization**.  

---

## 📂 Project Structure
- `insurance_sex_analysis.ipynb` → Jupyter Notebook with full code, analysis, and plots  
- `requirements.txt` → Required Python libraries  
- `README.md` → Project documentation  

---

## 📊 Dataset
The dataset comes from [Machine Learning with R Datasets](https://github.com/stedy/Machine-Learning-with-R-datasets).  
It contains **1,338 observations** with the following columns:  
- `age` → Age of the primary beneficiary  
- `sex` → Gender (`male`, `female`)  
- `bmi` → Body mass index  
- `children` → Number of children covered by health insurance  
- `smoker` → Smoker/non-smoker  
- `region` → Residential area in the US  
- `charges` → Medical insurance costs (target variable)  

For this project, we focused only on **sex → charges**.  

---

## 🧪 Methods
1. **Preprocessing**  
   - Encoded `sex` into numeric values (`0 = female`, `1 = male`).  

2. **Exploratory Data Analysis (EDA)**  
   - Visualized average and distribution of charges by sex using **barplots and boxplots**.  

3. **Modeling**  
   - Ran a **Simple Linear Regression** to check if sex predicts insurance charges.  

4. **Statistical Testing**  
   - Performed an **independent t-test** to test for mean differences between male and female charges.  

---

## Results
- **Regression**: Sex explained very little variance in charges (low R²).  
- **t-test**: A statistically significant difference was found (*t* = 2.09, *p* = 0.036).  
- **Interpretation**: While the difference is statistically significant, the effect size is small. Stronger predictors of charges include **smoking status, age, and BMI**.  

