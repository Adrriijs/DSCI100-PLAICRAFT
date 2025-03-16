# DSCI100-PLAICRAFT

## **Project Overview**  
This project is part of **DSCI 100** at **UBC** and aims to analyze player behavior in **PLAICRAFT** using data from `players.csv`. The goal is to understand which types of players contribute the most data by examining the relationship between **age, gender, and total playtime**. By focusing on **Regular** players, we aim to identify trends that can inform player engagement strategies.

## **Dataset**  
- **File Used**: `players.csv`  
- **Key Variables**:  
  - `experience`: Player's skill level (**Pro, Veteran, Amateur, Regular**)  
  - `age`: Player's age in years  
  - `gender`: Player's gender (**Male, Female, Non-binary**)  
  - `played_hours`: Total playtime accumulated by the player  

## **Methods**  
- **Data Wrangling**: Removing missing values, filtering for `Regular` players, and selecting relevant variables.

## **Future Methods** 
- **Exploratory Analysis**: Using `ggpairs` and scatter plots to examine relationships between variables.  
- **Modeling**: Applying **linear regression** to analyze how `age` and `gender` influence `played_hours`.  
- **Evaluation**: Using **RMSE** and **RMSPE** to assess model accuracy.  

## **Findings**  
The analysis showed that most players have **low playtime (under 10 hours)**, with a few **15-25-year-olds** showing **extremely high playtime (150+ hours)**. There was **no strong correlation** between age and playtime, challenging the idea that younger players accumulate more hours. Additionally, **male players were more frequent**, but extreme playtime outliers were observed across all gender categories, indicating that engagement is **not gender-dependent**.

## **Next Steps**  
- Further investigation into **outliers** to ensure data accuracy.  
- Exploring additional factors such as **subscription status** or in-game actions.  
- Refining the model to improve predictive performance.

## **Accessing the HTML Report**  
You can access the **HTML version** of the report by **downloading** it first before opening it in your browser.

## **Contributors**  
This project was completed as part of **DSCI 100 (Data Science at UBC)**. 
