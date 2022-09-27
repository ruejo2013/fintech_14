# Machine Learning Trading Bot
-
## Table of Contents

1. Project Motivation
2. About the Application
3. Project Overview
4. How to Run
5. File Descriptions
6. License

## Project Motivation
This project is in completion of the Columbia University FinTech 2022 bootcamp module fourteen weekly challenge exercise.

---

## About the Application
Python code is use to process data, build, train and test machine learning models, used by a Financial assest management company to manage and automatically trade financial assests.

## Project Overview
In this project, different machine models were trained, tested and their performance evaluated in the steps listed below
1. Prepare the data (dropna's, add signal column)
2. Scale the data
3. Split the data to train and test set, using 3 months offset daterange
4. Create support vector machine (SVM) instance
5. Fit the model
6. Predict the data using the testing dataset
7. Evaluate the model
8. Create and save a cumulative line chart of the Actual and Strategy Returns of the dataframe
9. Create LogisticRegression model
10. Fit the model
11. Predict the data using the testing dataset
12. Evaluate the logisticRegression model 
13. Tune the dataset, using 6 months offset daterange
14. Create support vector machine (SVM) instance
15. Fit the model
16. Predict the data using the testing dataset
17. Create and save a cumulative line chart of the Actual and Strategy Returns of the dataframe
18. Compare the SVM models (tuned dataset performance vs the original datasets)

---
## How to Run
Follow steps in the snippet below to install libaries, and to run the application.

```
git clone <link to repo>
open and run machine_learning_trading_bot.ipynb 
<see below image>

```

![alt text](/Starter_Code/Resources/how_to_run.png)


## File Descriptions
There are one folders, one sub-folder and one file in the fintech_11 folder:
1. Starter_Code
 - machine_learning_trading_bot.ipynb 
 - Resources
   - emerging_markets_ohlcv.csv
   - how_to_run.png
   - cum_plot.png
   - cum_plot_tuned.png

2. README.md
3. requirements.txt

## Conclusion
Looking at both charts we can conclude that using the tuned dataset (sencond SVM model) the margin of 
Strategy Returns was greater from early 2020 and onwards, and would have yeilded more ROI for the company as against using the 
first SVM model with the original dataset.
### Tuned Dataset

![alt text](/Starter_Code/Resources/cum_plot_tuned.png)

### Original Dataset

![alt text](/Starter_Code/Resources/cum_plot.png)

    
## License
This project is in completion of the Columbia University FinTech 2022 bootcamp module fourteen weekly challenge exercise. It should not be copied and used for commercial purpose without the authorization of the admin on this repo. For futher information please contact Patrick via email on pruejoma@gmail.com