## Project 2

Steps followed:
* Handling Missing Values: \
  We can either 
    * Drop row / column
    * Replace data 
  But dropping rows is not effiecient since we have very less number of rows. So instead replace those missing values with meaningful replacements like average or mode
* Checking datatypes of columns and correcting if necessary: \
  We replace the columns with string datatypes to integer values using pandas factorize function
* Building a model (without L1 regularizer): \
  For this part we have chosen 'categorical_crossentropy' as our loss function, since it was the one giving highest accuracy
* Building another model (with L1 regularizer)  
* Writing code to find the symbol for a single datapoint using the trained model
