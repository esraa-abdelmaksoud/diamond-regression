# Diamond Price Prediction

Predicting the price of diamonds depends on multiple features such as the color, carat, and the dimensions of the diamond. As a part of a Kaggle competition for predicting diamond price, regression models were trained to solve this problem.

**Features**

1. Carat: Weight of the Diamond (0.2-5.01)
2. Cut: Quality of the diamond cutting. (Worst to Best: Fair, Good, Very Good, Premium, and Ideal)
3. Color: Color of the Diamond. (Best to Worst: D, E, F, G, H, I, and J)
4. Clarity: Absence of the Inclusions and Blemishes. (Best to Worst: I1, SI2, SI1, VS2, VS1, VVS2, VVS1, and IF)
5. x: length in mm. (0-10.74)
6. y: width in mm. (0-58.9)
7. z: depth in mm. (0-31.8)
8. depth: total depth percentage = z / mean(x, y) = 2 * z / (x + y) (43--79)
9. table: width of top of diamond relative to widest point (43--95)
10. Price: the Price of the Diamond

![image](https://user-images.githubusercontent.com/73304837/194354941-436e18ef-136f-4096-bcbd-a44bb2e5522c.png)

![image](https://user-images.githubusercontent.com/73304837/194354968-ca36bc39-3c9d-40f0-883e-8ca7d7985838.png)

**Models**

The models that were used to predict the prices are:
1. Linear Regression
2. Decision Trees
3. Random Forests
4. SVM

**Error**

Mean Squared Error (MSE) and Root Mean Squared Error (RMSE) were used to measure the error.
