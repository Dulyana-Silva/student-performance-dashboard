# Student Performance Dashboard 

A data analysis and visualization project exploring how student habits impact academic performance using Python, pandas, and matplotlib.

---
## About Dataset
This is a simulated dataset exploring how lifestyle habits affect academic performance in students. With 1,000 synthetic student records and 15+ features including study hours, sleep patterns, social media usage, diet quality, mental health, and final exam scores. It's structured, clean, and ready for exploration, modeling, and storytelling

Ever wondered how much Netflix, sleep, or TikTok scrolling affects your grades? 👀 This dataset simulates 1,000 students' daily habits—from study time to mental health—and compares them to final exam scores. It's like spying on your GPA through the lens of lifestyle.

## About Data
### Quantitative (Numerical) Variables:
- age
- study_hours_per_day
- social_media_hours
- netflix_hours
- attendance_percentage
- sleep_hours
- exercise_frequency
- mental_health_rating
- exam_score (dependent/target variable)

### Qualitative (Categorical) Variables):
- gender (Male, Female, Other)
- part_time_job (Yes/No)
- diet_quality (Poor, Fair, Good)
- parental_education_level (High School, Bachelor, Master)
- internet_quality (Poor, Average, Good)
- extracurricular_participation (Yes/No)
  
## Techniques Used
### 🧪 Jupyter notebook
 - Jupyter Notebook is an open-source web application that allows you to create and share documents that contain live codes, visualizions.
 - You can write and run code, see outputs instantly under the code cells, and create reports that combine text and visuals in one place.
 
### 🐼 Pandas
- Pandas is a powerful Python library used for data manipulation and analysis.
- In this project, pandas was used for loading and inspecting the dataset, performing exploratory data analysis (EDA) and calculating summary statistics and trends

### 📊 Matplotlib
- Matplotlib is a comprehensive library for creating static, animated, and interactive visualizations in Python.
- It was used to generate various plots (such as bar charts, histograms, and pie charts) that helped visualize the relationships between student habits and academic performance.

### 📈 Seaborn
- Seaborn is a powerful Python library for statistical data visualization, built on top of Matplotlib.
- It works seamlessly with pandas DataFrames and makes complex visualizations like heatmaps and box plots easy to generate and interpret.


## Here's the angles we're goning to pursue

🔎 Correlation & Relationship Analysis:
- Does study time have a strong positive impact on exam score? 
- How does sleep vs. social media use affect exam performance?
- What’s the relationship between mental health rating and exam score?
- Does having a part-time job reduce scores due to less study time/sleep?

📊 Group Comparisons:
- Do students with better internet score higher?
- Is there a gender-based performance gap?
- Compare diet quality vs. exam score.
- Compare parental education level vs. student performance.

📉 Risk Factor Exploration:
- What combination of habits is most common in low scorers?
- Are there clusters of habits that define high vs. low performers?

  
## 🔗 Correlation Analysis (Correlation Heatmaps)
The heatmap below shows relationships between numerical variables. We observe a strong positive correlation between study hours and exam score, and a slight negative correlation with social media and Netflix usage.

## 📈 Relationship Analysis (Regression Plots)
We visualize how key habits like study hours, sleep, and social media usage relate to exam scores. Trend lines help understand whether habits positively or negatively impact performance.

## 🧪 Group Comparisons (Boxplots)
Here, we compare exam scores across different student groups based on:
- Gender
- Parental education level
- Diet quality
- Part-time job status

## 🌟 Top Performer Profile
We filter students scoring above 85 and analyze their typical habits. This helps us understand the lifestyle choices of successful students.

## ⚠️ Risk Factor Exploration (Low Scorers)
We focus on students scoring below 60 and explore common patterns among them. This can help identify habits associated with lower academic performance.

### 🧠 Who Are the Top Performers?

Students scoring 85 or above tend to study around 5 hours per day, sleep 6 hours, and maintain a high attendance percentage.
Most top performers reported having Average internet quality and did not participate in extracurricular activities.
Interestingly, a majority of them did not work part-time and followed a Fair diet.
This suggests that consistent study habits and mental health may play a bigger role than distractions like social media or Netflix.

### 📉 Risk Profile of Low Scorers

Students scoring below 40 tend to show different lifestyle patterns compared to top performers.
They generally:
- Study fewer hours and have comparatively lower attendance
- Spend more time on social media and Netflix
- Report lower mental health ratings
- Are more likely to have poor diet quality.

They mental health shows a signnificant drop and study houring are comparatively low also that having a poor diet comparatively to the topper.

## 📝 Conclusion
This analysis reveals several key insights:
- 📚 **Study hours** and **mental health** positively impact exam performance.
- 📱 **Excessive social media** and poor **diet** are linked to lower scores.

This project demonstrates how data science can uncover real-world educational patterns that support better learning outcomes.

---
