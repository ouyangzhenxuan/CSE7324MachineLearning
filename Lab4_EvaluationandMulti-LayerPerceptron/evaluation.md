Because we are going to use the grid search, the cross validation will be run several times. Using the nested cross validation is efficient. We can run the program just once to test all parameters and find the winning model.     
And we will use the stratified 10-fold cross validation as well.      
The reason for using stratified 10-fold cross validation is this method can guarantee the proportion of the data in 3 sets is as same as the original dataset. So the model we get will fit the dataset.   
According to the above, the nested cross validation with the grid search and stratified 10-fold cross validation are appropriate for us.
