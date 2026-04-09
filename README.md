# Titanic Survival Analysis — Pandas Project

## Overview
This project analyzes the **Titanic dataset** (`train.csv`) using **Python and Pandas** in Google Colab.  
The goal is to explore, clean, analyze, and extract insights about passenger survival based on **gender, class, and age**.  



## Dataset
- **Source:** Kaggle Titanic: Machine Learning from Disaster (`train.csv`)  
- **Columns include:**  
  - PassengerId, Survived, Pclass, Name, Sex, Age, SibSp, Parch, Ticket, Fare, Cabin, Embarked  



## Steps Performed

### **Part 1: Create Your Own Dataset**
- Built a sample dataset with **5 features** and **15 rows**  
- Assigned **custom index** for practice  

### **Part 2: Titanic Dataset Analysis**

**1. Exploration**
- `.head()`, `.info()`, `.describe()` to understand data  
- Checked missing values and data types  

**2. Data Cleaning**
- Filled missing `Age` with **median**  
- Filled missing `Embarked` with **mode**  
- Dropped `Cabin` column  
- Removed duplicates  

**3. Data Analysis (groupby)**
- Survival rate by **gender**  
- Survival rate by **class**  
- Average age per class  
- Survival rate by **age group**  

**4. Filtering**
- Female passengers who survived  
- Children who survived (age ≤ 12)  
- 1st class passengers who survived  

**5. Insights**
- **Gender:** Females were more likely to survive  
- **Class:** Higher-class passengers had higher survival rates  
- **Children:** Prioritized with higher survival  
- **Highest survival combination:** Female passengers in 1st class (~97%)  



## Tools Used
- **Python 3.x**  
- **Pandas**  
- **Google Colab**  



## How to Run
1. Open the notebook `Titanic_Task3.ipynb` in Colab  
2. Make sure `train.csv` is in the same folder or uploaded in Colab  
3. Run each cell sequentially to reproduce analysis  


## Notes
- All analysis is done using **Pandas only**  
- Code is **clean and readable**, with handling of missing values  
- Future improvements could include visualizations with **Matplotlib or Seaborn**  
