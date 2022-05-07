# Neural_Network_Charity_Analysis

1.  **Overview of the analysis:**  The purpose of this analysis is to utilize neural networks in order to create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.
    
2.  **Results:**  
    
    -   _Data Preprocessing_
        -  EIN and Name were removed from the data as they do not relate to the success measures

    -   _Compiling, Training, and Evaluating the Model_
        -   A two layer model was used. The first layer has 10 neurons, and the second layer has 5. 
        -   Accuracy was below the 75% threshold using these metrics
        ![enter image description here](https://github.com/ozzirk/Neural_Network_Charity_Analysis/blob/main/50%20Epochs.jpg?raw=true)
        -   In order to increase accuracy, attempts were made to strengthen the model by increasing the number of epochs from 50 to 60, which did not yield a significant difference.
        ![enter image description here](https://github.com/ozzirk/Neural_Network_Charity_Analysis/blob/main/60%20Epochs.jpg?raw=true)
        - The second attempt included changing the first layer methodology from sigmoid to relu, and still using 60 epochs. There was also limited success with this method. This did increase the accuracy, but not significantly enough.
        ![enter image description here](https://github.com/ozzirk/Neural_Network_Charity_Analysis/blob/main/Relu.jpg?raw=true)
3.  **Summary:**  Overall, the results of these models were strong, but did not meet the desired threshold of 75% or higher accuracy. Further testing may show that Relu should be used for both layers in order to increase accuracy. More testing would be required.
