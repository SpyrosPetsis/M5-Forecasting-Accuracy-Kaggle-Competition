# M5-Forecasting-Accuracy 
  In this competition, the fifth iteration, we will use hierarchical sales data from Walmart, the world’s largest company by revenue, to forecast daily sales for the next 28 days. The data, covers stores in three US States (California, Texas, and Wisconsin) and includes item level, department, product categories, and store details. In addition, it has explanatory variables such as price, promotions, day of the week, and special events. Together, this robust dataset can be used to improve forecasting accuracy.
  
  The file with the code (m5-competition-accuracy-uom-mbads-final.ipynb) contains all the stages of the analysis. We tried to create a dynamic model with drop down menus. 
The first drop down menu gives the opportunity to the user to select the category of the product (hobbies,household,foods and all the products regardless of their category).    After the user selects the range of sales he wants and the product he wants based on the range. Finally he can select some visualizations like daily sales, monthly sales, sales    by weekday, quarter and year, but he can also select one of the three algorithms for prediction (FBProphet,XGBoost,RandomForest).

Here is a link with informations about this kaggle competition  https://www.kaggle.com/c/m5-forecasting-accuracy/overview/description  and also you can find the files at this link https://www.kaggle.com/c/m5-forecasting-accuracy/data. We used the calendar.csv,sales_train_evaluation.csv and sales_train_validation.csv. The sales_train_evaluation.csv file 
constitutes the train dataset and the sales_train_validations.csv file contains all the sales with the next 28 daily sales and we used it to measure the accuracy of the model.

In the video you can see the functions of the drop-down menus. You can copy the code at your local jupyter notebook but you must download the files or you can send me a message to send you the zip file with all files in to upload it at your jupyter notebook. 

Have fun and thank you for your attention
