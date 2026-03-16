# 🎬 Netflix Movie Data Analysis

##  Project Overview
This project analyzes a Netflix-style movie dataset to discover patterns in movie genres, ratings, and popularity.  
The analysis is performed using Python data analysis and visualization libraries to extract meaningful insights from the dataset.

This project demonstrates **Exploratory Data Analysis (EDA), data cleaning, and data visualization skills** using real-world movie data.

---

##  Dataset
The dataset contains information about movies such as:

- Movie Title
- Genre
- Vote Average (Rating)
- Popularity
- Release Date
- Other movie-related attributes

---

##  Technologies Used

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**

---

##  Project Workflow

###  Data Loading
The dataset was loaded using Pandas.

```python
import pandas as pd

df =pd.read_csv('/content/mymoviedb.csv',lineterminator='\n')df = pd.read_csv("mymoviedb.csv", lineterminator='\n')
df.head()
```

---

###  Data Exploration

Basic exploration was performed to understand the dataset.

```python
df.info()
df.describe()
df['Genre'].head()
```

---

###  Data Cleaning

Steps performed:

- Checked missing values
- Removed duplicate records
- Examined categorical variables
- Prepared dataset for analysis

---

###  Exploratory Data Analysis (EDA)

Key analyses performed:

- Distribution of movie ratings
- Genre frequency analysis
- Popularity trends
- Statistical summary of dataset

---

###  Data Visualization

Example visualization:

<img width="800" height="633" alt="image" src="https://github.com/user-attachments/assets/a8016cdd-b0f9-446f-906d-4b650924f910" />

<img width="878" height="548" alt="image" src="https://github.com/user-attachments/assets/b6afd475-be61-49a6-9d05-ec9939147057" />

<img width="891" height="550" alt="image" src="https://github.com/user-attachments/assets/d2640176-25c9-416c-8a3f-ae16055fae2f" />

<img width="905" height="537" alt="image" src="https://github.com/user-attachments/assets/da380e92-fc7c-4afd-8d45-68bdfda567fa" />

<img width="860" height="550" alt="image" src="https://github.com/user-attachments/assets/e5150c90-5344-4ec9-8751-bb8cb076c70a" />










---

##  Key Insights

- Some genres appear more frequently than others.
- Movie ratings are concentrated in specific ranges.
- Popularity varies significantly between movies.
- Visualization helps identify patterns in the dataset.

---

##  Future Improvements

Possible improvements for this project:

- Build a **Movie Recommendation System**
- Predict movie ratings using **Machine Learning**
- Create an **interactive dashboard**
- Perform deeper **genre trend analysis**

---

