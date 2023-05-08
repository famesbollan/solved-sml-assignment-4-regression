Download Link: https://assignmentchef.com/product/solved-sml-assignment-4-regression
<br>



<ol>

 <li>Implement the normal equation (closed form) regression for the <a href="https://www.cs.toronto.edu/~delve/data/boston/">Bosto</a>​ <a href="https://www.cs.toronto.edu/~delve/data/boston/">n</a> <a href="https://www.cs.toronto.edu/~delve/data/boston/">housing</a> <a href="https://www.cs.toronto.edu/~delve/data/boston/">dataset.</a> The dataset description can be found <a href="https://www.cs.toronto.edu/~delve/data/boston/bostonDetail.html">her</a><u>​ </u><a href="https://www.cs.toronto.edu/~delve/data/boston/bostonDetail.html">e</a>.​ The target feature is variable no. 14, ’MEDV’, and the input variables are the remaining 13 variables.</li>

</ol>




<ol>

 <li>Divide the dataset into training and testing using an 80:20 split ratio.</li>

 <li>Perform Linear regression for all features and compute the RMSE for training as well as the testing set. (​<strong>Note:</strong> There is no need to perform k-fold cross-validation for this part.)</li>

 <li>Select the feature named ‘LSTAT’ for polynomial regression.</li>

 <li>Perform k-fold cross-validation for k=5 on the training dataset. (<strong>Note:</strong>​ You can not use any inbuilt library to implement k-fold cross-validation.)</li>

 <li>Perform step (d) for different degrees of polynomials using Polynomial Regression (Ex. For degree=1 perform 5-fold cross-validation, For degree=2, perform 5-fold cross-validation and so on.)</li>

 <li>Use RMSE as an evaluation metric (<strong>Note:</strong>​ You can’t use any inbuilt library for it). Compute mean RMSE of training and validation set separately from 5-fold cross-validation for each degree of the polynomial and plot it.</li>

 <li>Choose the degree of a polynomial with the least mean validation RMSE and use that degree of polynomial to perform final regression on the whole training dataset (i.e., 80% dataset). State the RMSE of the test dataset (i.e., 20% dataset).</li>

</ol>




<ol start="2">

 <li>Use the following <a href="https://drive.google.com/file/d/1niBXPPkvt-RvCrAWFDUiqmEf6z__GUY8/view?usp=sharing">dat</a>​ <a href="https://drive.google.com/file/d/1niBXPPkvt-RvCrAWFDUiqmEf6z__GUY8/view?usp=sharing">a</a> that contains only 1 input feature and 1 target variable i.e X and Y. Consider the dataset as a whole i.e. Don’t split it into train or test data.</li>

</ol>




<ol>

 <li>Perform the steps (d), (e), (f) of Part-1.</li>

 <li>Show the plots of line/curve fitted for the dataset using the different degrees of polynomials (degree). I.e, degree = [1,2,4,5,10,15,30]. Compute and state their RMSE also.</li>

</ol>




<strong>Note: Mention all the observations, results, analysis, visualizations and experiments in the report for each part (if any). </strong>


