# Black-Friday-Sales-Prediction

![Black Friday Sales images](https://github.com/user-attachments/assets/4bde8936-54b7-440c-8bdc-968628cf00c9)



#### Conclusion on Regression Models Performance

    After evaluating multiple regression models, we can draw the following conclusions based on their Mean Squared Error (MSE) and R-squared (R²) values:

1. Linear Regression

    MSE: 3.671

    R²: 0.896
    
Conclusion: Linear Regression performs well with high prediction accuracy and low error, indicating a good fit for the data.

2. Decision Tree Regression

    MSE: 5.197
    
    R²: 0.853 
    
Conclusion: Decision Tree Regression has higher error and lower R² compared to other models, suggesting it may not capture the underlying pattern as effectively.

3. Support Vector Regression (SVR)

    MSE: 4.510

    R²: 0.873
    
Conclusion: SVR shows good performance but with slightly higher error compared to Linear Regression.

4. Random Forest Regression

    MSE: 4.365

    R²: 0.877
    
Conclusion: Random Forest Regression performs well with a good balance between prediction accuracy and error.

5. Polynomial Regression


    MSE: 3.646

    R²: 0.897
    
Conclusion: Polynomial Regression slightly outperforms Linear Regression, indicating it captures the non-linear relationships in the data well.

6. Lasso Regression

    MSE: 3.662

    R²: 0.897
    
Conclusion: Lasso Regression performs similarly to Linear and Polynomial Regression, showing its effectiveness in handling high-dimensional data.

7. Ridge Regression

    MSE: 3.669

    R²: 0.897
    
Conclusion: Ridge Regression also performs comparably to Linear and Polynomial Regression, demonstrating its ability to handle multicollinearity.

8. K-Nearest Neighbors Regression (KNN)

    MSE: 5.401

    R²: 0.848
    
Conclusion: KNN Regression has the highest error and lowest R², indicating it may not be the best choice for this dataset.

#### Visual Analysis of Regression Models

![Support Vector Regression Prediction](https://github.com/user-attachments/assets/e7fea527-67e3-44d6-acc0-b0bbaf562bfe)
![Ridge Regression Prediction](https://github.com/user-attachments/assets/785d76b8-3212-4f51-8f0b-1e5b0f5b1db2)
![Random Forest Regression Prediction](https://github.com/user-attachments/assets/22aef768-35a2-4a97-b631-26f67f4e59c7)
![Polynomial Regression Prediction](https://github.com/user-attachments/assets/b06a149b-9d3a-40aa-8fa2-e02a8820c981)
![Linear Regression Prediction](https://github.com/user-attachments/assets/2ac3643b-2caa-43cb-aa2c-787378f5d2c7)
![Lasso Regression Prediction](https://github.com/user-attachments/assets/ffae9b0e-3cbc-4a85-93a2-16dd3a0541d1)
![K-Nearest Neighbors Regression Prediction](https://github.com/user-attachments/assets/6a90725f-1e79-4d5e-88d4-aa3928780fe8)
![Decision Tree Regression Prediction](https://github.com/user-attachments/assets/28517a0e-f7d9-4e72-b63f-024b62b8943f)


From the visual plots provided, we can further infer:

Linear, Lasso, and Ridge Regression: These models show a clear linear trend and good alignment with the true data points.

Decision Tree and Random Forest Regression: These models capture more complex patterns but with slightly more variance.

KNN Regression: Shows a scattered prediction pattern, which aligns with its higher error metrics.

SVR: Demonstrates a balanced prediction performance with a clear trend line.

Overall Conclusion

    Top Performers: Linear Regression, Polynomial Regression, Lasso Regression, and Ridge Regression show the best 
    performance with low MSE and high R² values.

    Moderate Performers: Random Forest Regression and SVR also perform well but with slightly higher errors.

    Least Performers: Decision Tree Regression and KNN Regression exhibit higher errors and lower R² values, making them less effective for this dataset.

    Selecting the best model depends on the specific requirements and complexity of the problem. For this dataset, Linear Regression, Polynomial Regression, Lasso, and Ridge Regression are recommended due to their balance of accuracy and simplicity.
