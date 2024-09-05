# What do your blood sugars tell you?

## 📖 Background

Diabetes mellitus remains a global health issue, causing several thousand people to die each day from this single condition. 
Finding and avoiding diabetes in the earlier stages can help reduce the risk of serious health issues such as circulatory system diseases, kidney malfunction, and vision loss.
This competition involves developing a predictive model for effectively detecting potential Diabetes cases, ideally, before commencing preventive treatment.

## 💾 The data

The dataset contains diagnostic measurements that are associated with diabetes, which were collected from a population of Pima Indian women. The data includes various medical and demographic attributes, making it a well-rounded resource for predictive modeling.

The columns and Data Types are as follows:

- Pregnancies
Type: Numerical (Continuous)
Description: Number of times the patient has been pregnant.

- Glucose
Type: Numerical (Continuous)
Description: Plasma glucose concentration a 2 hours in an oral glucose tolerance test.

- BloodPressure
Type: Numerical (Continuous)
Description: Diastolic blood pressure (mm Hg).

- SkinThickness
Type: Numerical (Continuous)
Description: Triceps skinfold thickness (mm).

- Insulin
Type: Numerical (Continuous)
Description: 2-Hour serum insulin (mu U/ml).

- BMI
Type: Numerical (Continuous)
Description: Body mass index (weight in kg/(height in m)^2).

- DiabetesPedigreeFunction
Type: Numerical (Continuous)
Description: A function that represents the likelihood of diabetes based on family history.

- Age
Type: Numerical (Continuous)
Description: Age of the patient in years.

- Outcome
Type: Categorical (Binary)
Description: Class variable (0 or 1) indicating whether the patient is diagnosed with diabetes. 1 = Yes, 0 = No.


# **Conclusion**

### 1. **Glucose Levels**:
   - **Most Critical Factor**: High glucose levels are the most strongly associated with diabetes. Diabetic individuals (Outcome = 1) consistently show elevated glucose levels, often exceeding 200 mg/dL. The scatter plot and line plot both highlight this as a primary determinant of diabetes.
   - **Normal Range for Non-Diabetics**: Non-diabetic individuals (Outcome = 0) typically have glucose levels in the range of 80-125 mg/dL. This makes glucose a clear differentiator between diabetic and non-diabetic individuals.

### 2. **Body Mass Index (BMI)**:
   - **Weight and Glucose Connection**: Higher BMI is associated with increased glucose levels, especially in diabetic individuals. There is a clear trend showing that individuals with a higher BMI tend to have higher glucose levels, reinforcing the connection between obesity and diabetes risk.
   - **Weight Management**: Losing weight can lower BMI, which in turn may help reduce glucose levels and manage diabetes or even prevent it in at-risk individuals.

### 3. **Pregnancy History** (Number of Times Pregnant):
   - **Increased Diabetes Risk with Higher Pregnancy Numbers**: The violin plot shows that diabetic individuals tend to have a broader distribution of pregnancy numbers, with a secondary peak at higher pregnancy counts. This suggests that the **number of pregnancies** could be a factor increasing the risk of developing diabetes. 
   - **Non-Diabetic Individuals**: In contrast, non-diabetic individuals tend to have lower pregnancy numbers, with a sharp peak indicating that most non-diabetics have fewer pregnancies.

### 4. **Diabetes Pedigree Function**:
   - **Genetic Influence**: The violin plot reveals that a higher Diabetes Pedigree Function (which reflects family history) is linked to an increased likelihood of diabetes. Diabetic individuals tend to have a broader distribution of pedigree function scores, with a noticeable secondary peak at higher values. 
   - **Genetics vs. Environment**: While genetics play an important role, environmental factors and lifestyle choices are also crucial. Not all individuals with a high pedigree function develop diabetes, indicating that genetics alone does not determine the outcome.

### 5. **Age**:
   - **Age-Related Glucose Increase**: The line plot shows that glucose levels tend to rise with age, particularly after 50. While age alone is not a consistent predictor of diabetes (as seen in the scatter plot), it is an important factor that interacts with other variables, such as glucose levels and BMI, to increase diabetes risk.
   - **Age and Diabetes Distribution**: The violin plot shows multiple peaks for diabetic individuals, indicating that diabetes risk increases with age, particularly in the 25-32 and 39-56 age ranges. Non-diabetic individuals are more concentrated at younger ages, with the prevalence decreasing as they get older.

### 6. **Other Factors (Interacting Variables)**:
   - **Complex Relationships**: The combination of age, genetics (Diabetes Pedigree Function), BMI, and pregnancy history all interact in complex ways to influence diabetes outcomes. These factors do not act independently; instead, they work together, influencing an individual’s overall risk of developing diabetes.
