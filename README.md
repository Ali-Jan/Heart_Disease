# Heart Disease Dashboard

This repository contains a Power BI dashboard built using a real dataset of heart disease patients from the [Heart Disease Cleveland UCI Repository](https://www.kaggle.com/datasets/cherngs/heart-disease-cleveland-uci/data). The dashboard provides insights into various clinical and demographic attributes to support data-driven decisions and health analytics.

## Dataset Overview
The dataset consists of 13 features, all of which are numerical. Some features are inherently categorical and have been encoded accordingly. Below is a detailed description of the dataset:

### Features:
1. **age**: Number of years a person has lived.
2. **sex**: Gender of the patient (1 = Male, 0 = Female).
3. **cp**: Chest pain type (4 values).
4. **trestbps**: Resting blood pressure (in mm Hg).
5. **chol**: Serum cholesterol (in mg/dl).
6. **fbs**: Fasting blood sugar > 120 mg/dl (1 = True, 0 = False).
7. **restecg**: Resting electrocardiographic results (0, 1, 2).
8. **thalach**: Maximum heart rate achieved.
9. **exang**: Exercise-induced angina (1 = Yes, 0 = No).
10. **oldpeak**: ST depression induced by exercise relative to rest.
11. **slope**: The slope of the peak exercise ST segment.
12. **ca**: Number of major vessels (0-3) colored by fluoroscopy.
13. **thal**: Thalium stress test results (3 = Normal, 6 = Fixed defect, 7 = Reversible defect).

### Target Variable:
- **condition**: Diagnosis of heart disease based on angiographic disease status:
  - **0**: < 50% diameter narrowing (negative for disease).
  - **1**: > 50% diameter narrowing (positive for disease).

---

## Dashboard Overview
The Power BI dashboard is organized into three main tabs:

### 1. **Patient Overview**
This tab provides a high-level summary of the dataset:

![Screenshot (10)](https://github.com/user-attachments/assets/8ea4abcf-3e25-4ab7-956f-f43664b63f59)


- **Slicers**:
  - Age window.
  - Gender.
- **KPIs**:
  - Total Patients (Participants).
  - Average Age.
  - Average Cholesterol.
  - Average Resting Blood Pressure.
  - Average Thalach (Maximum Heart Rate Achieved).
- **Bar Chart**:
  - Displays average differences between patients with heart disease and those without:
    - Average Age: +4 years for heart disease patients.
    - Average Cholesterol: +9 mg/dl for heart disease patients.
    - Average Resting BP: +4 mm Hg for heart disease patients.
    - Average Thalach: -20 BPM for heart disease patients.
- **Gender Analysis**:
  - Male patients with heart disease: 44% Yes, 56% No.
  - Female patients with heart disease: 26% Yes, 74% No.
  - Overall dataset ratio: 46% Yes, 54% No.

### 2. **Clinical Insights**
This tab delves into more detailed clinical analysis:

![Screenshot (11)](https://github.com/user-attachments/assets/27b5b5f1-619e-401d-8938-1ce776a96f38)

- **Scatter Plots**:
  - Oldpeak vs. Age.
  - Cholesterol vs. Age.
  - Thalach vs. Age.
    - Trends observed:
      - Oldpeak and cholesterol increase with age.
      - Thalach decreases with age.
- **Bar Charts**:
  - Vertical bar charts for Age, Exercise-Induced Angina, and Thal.
  - Horizontal bar charts for Chest Pain (CP) and CA.
- **Slicers**:
  - Age window.
  - Gender.

### 3. **Info Tab**
This tab provides:

![Screenshot (12)](https://github.com/user-attachments/assets/ffb7dd3b-d898-489e-b116-e0755550023a)

- General information about the dataset.
- Insights into heart disease statistics worldwide and in the U.S.
- Link to the dataset:  [Heart Disease Cleveland UCI Repository](https://www.kaggle.com/datasets/cherngs/heart-disease-cleveland-uci/data)
                        [UCI Heart Disease Dataset](https://archive.ics.uci.edu/dataset/45/heart+disease).

---

## How to Use
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Ali-Jan/Heart_disease_dashboard.git
   ```
2. Open the Power BI file (.pbix) to explore the dashboard.
3. Adjust slicers for Age and Gender to filter and analyze the data.

---

## Future Improvements
I am open to feedback and suggestions for enhancing this dashboard. Feel free to create an issue or submit a pull request if you have ideas for improvement.

---

## Contribute
- Like, share, or comment to help this dashboard reach health professionals and data enthusiasts.
- Share your insights and feedback to make this tool more valuable for the community.


---

## Contact
For any questions, feel free to connect on LinkedIn or raise an issue in the repository.
www.linkedin.com/in/AliJanAli3131


