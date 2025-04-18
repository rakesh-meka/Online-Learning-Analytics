# Online-Learning-Analytics
## 🔍 Overview
This project analyzes student course engagement and feedback data to provide insights into learning patterns and effectiveness. The analysis includes merging datasets, exploratory data analysis (EDA), and visualization of key metrics like course completion rates and engagement times.

## 📂 Project Structure
The project is organized in a Jupyter Notebook (`Student Engagement & Feedback Analysis.ipynb`) with the following main sections:

1. **Data Loading & Merging**
   - Loads three datasets: `students.csv`, `course_activity.csv`, and `feedback.csv`
   - Merges the datasets into a final combined dataset `Student Engagement & Feedback Analysis.csv`

2. **Exploratory Data Analysis (EDA)**
   - Calculates overall average completion rate across courses
   - Identifies courses with highest and lowest average engagement time
   - Examines how engagement differs by age group and location
   - Identifies correlation between completion rate and feedback rating
   - Identified top 3 student segments based on engagement and satisfaction.


## 📊 Key Findings

### ✅ Course Completion Rates
- The average completion percentage across all courses is approximately **54.78%**
- **UX303** has the highest average completion rate at **56.2%**
- **DM101** has the lowest average completion rate at **52.6%**

### ⏱️ Engagement Time Analysis
- **DM101** has the highest average engagement time at **102.43 minutes**
- **PY202** has the lowest average engagement time at **93.90 minutes**

### 📄 Data Description
The final merged dataset contains **659 entries** with **12 columns**:
- Course interaction: `Student_ID`, `Course_ID`, `Date`, `Time_Spent_Minutes`, `Completion_Percentage`
- Student details: `Name`, `Age`, `Gender`, `Location`, `Enrolment_Date`
- Feedback data: `Rating`, `Feedback_Text`

## ⚙️ How to Use
1. Clone the repository
2. Ensure Python and Jupyter Notebook are installed
3. Install required libraries using pip: `pandas`, `matplotlib`, `seaborn`, `numpy`
4. Open and run `Course_Insights.ipynb` to reproduce all analysis and visualizations

## 📦 Dependencies
- Python 3.x
- pandas
- matplotlib
- seaborn
- numpy
- scikit-learn
- scipy

## 📁 Dataset Sources
The analysis uses the following three CSV files:
1. `students.csv` - Contains student demographic information
2. `course_activity.csv` - Contains course engagement metrics
3. `feedback.csv` - Contains student feedback on courses

## 📜 License
This project is open source and freely available for educational, analytical, and non-commercial use.
