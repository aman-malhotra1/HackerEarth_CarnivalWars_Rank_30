# HackerEarth_CarnivalWars_Rank_30

Dataset_Link : https://www.hackerearth.com/practice/machine-learning/machine-learning-algorithms/beginners-guide-regression-analysis-plot-interpretations/practice-problems/machine-learning/predict-the-price-5-fe7f8735/

Leaderboard Link :  https://www.hackerearth.com/challenges/competitive/hackerearth-machine-learning-challenge-predict-selling-price/leaderboard/predict-the-price-5-fe7f8735/

In this HackerEarth competition , we have to predict the selling price of the product based on certain given features like Minimum Price , maximum price , Charges , discount , demand of the product .Apart from this Product category and market category is also given as feature column.

Findings -:
1) Minimum Price and Maximum Price are the highly correlated column to the target column selling price . 
2) Column charges_1 is related to column product category so null values in charges_1 column can be filled with the median value of charges_1 as per different products in product category.
3) Columns like Demand, charges_2, Discount_avail_2, Market_Category, Grade, Loyalty_customer has no effect on selling price so I dropped these columns while createing model.
