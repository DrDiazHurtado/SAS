# Mini SAS Project

Hey there! This is a mini SAS project. Here I’m playing around with a tiny medical-style dataset to show off some basic SAS skills. The dataset (`patients.csv`) includes 10 fictional patients with columns for age, gender, blood pressure, cholesterol, and a binary disease indicator.

---

## What’s in This Repo?

- **patients.csv**: Our small CSV file with patient data.  
- **SAS Scripts**: A bunch of `.sas` files demonstrating how to:  
  - Import the CSV into SAS  
  - Run basic descriptive stats  
  - Check frequencies and test for association (Chi-square)  
  - Calculate correlations  
  - Build a simple logistic regression model  
  - Plot a few graphs (scatter and boxplot)

---

## Why Do This?

- **Practice**: It’s a quick way to show you know your way around SAS.  
- **Demonstrate**: Basic analytics, from EDA to simple modeling, all in one place.  
- **Fun**: Who doesn’t like a quick, hands-on example?

---

## How to Use

1. Clone or download this repo.  
2. Open SAS (there is an online version avalaible for students) and point the `FILENAME` statement to the `patients.csv` location.  
3. Run the `.sas` scripts in the order you like (or just open them in SAS Studio).  
4. Check out the results (descriptive tables, frequencies, correlation matrix, regression output, and plots).

---

## What You’ll See

- **PROC CONTENTS**: Overview of dataset structure  
- **PROC MEANS**: Stats like mean, std dev, min, max for Age, BP, Cholesterol  
- **PROC FREQ**: Frequency tables + Chi-square test for Gender vs Disease  
- **PROC CORR**: Correlation among numeric variables  
- **PROC LOGISTIC**: Simple logistic regression to predict Disease  
- **PROC SGPLOT**: A few quick visualizations (scatter + boxplot)

---

## Next Steps

Feel free to tweak the dataset, add more observations, or swap in real clinical data if you have it (remember to respect privacy rules!). You can also extend the code to do more advanced modeling.

Enjoy exploring, and let me know if you have suggestions or find anything interesting!

**Happy SAS-ing!**  
— Marcos
