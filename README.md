## FruityRegression ##

Logistic Regression Model Trained to Identify Fruits on Sample with Acute Variability<br/>

## Summary ##

This Logistic Regression Model uses scikit-learn (https://scikit-learn.org/) method to train a model using logistic regression to identify fruits. <br/>

## Methods: ##
-The data set of images was split utilizing "train_test_split" : 75% training and 25% testing.<br/>
-Converted image arrays into 2-d arrays without degrading the numeric values associated with RGB values, "jpgarray.reshape(-1)."<br/>
-Plotted a confusion matrix. <br/>
-Tested the model on fruit images outside the dataset. <br/>
-Modified the confusion matrix to plot outside images on their predicted and actual values. <br/>

## Conclusions: ##

<img src="/Images/Fruit_Confusion_Matrix.png" height=400>
-The model predicted every image in the training set accurately. <br/>
-We received a mean accuracy score of 1.00, a perfect score.v<br/>
-We believe the data source lacks variability, give the model no room for error when test on images not too different from the images <br/>

<img src="/Images/Predicted_Classifications.png" height=400>
-When utilizing the model to predict the fruit classification of images outside the dataset, the model was found to be highly erroneous. <br/>

## Data Source: ##

Images are of the fruit subjects with a white background with the overall img dimmensions of 100 x 100. <br/>

"Fruits and vegetables were planted in the shaft of a low speed motor (3 rpm) and a short movie of 20 seconds was recorded.

A Logitech C920 camera was used for filming the fruits. This is one of the best webcams available.

Behind the fruits we placed a white sheet of paper as background."<br/>

Horea Muresan, Mihai Oltean, Fruit recognition from images using deep learning, Acta Univ. Sapientiae, Informatica Vol. 10, Issue 1, pp. 26-42, 2018.<br/>

<img src="/Images/Banana.png" height=200>
<img src="/Images/Pineapple.png" height=200>
<img src="/Images/Peach.png" height=200>
Three examples above are a snapshot of the images in the dataset. <br/>

