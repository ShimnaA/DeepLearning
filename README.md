**TensorFlow**

    Data - [DATA/fake_reg.csv]

        - Read in data, visualize a bit.
        - Scale data and create tensorflow model
        - Train and Evaluate
        - Predict on a new data, Save the model for later use
        
    Data - [DATA/kc_house_data]

        - Read in data, perform EDA 
        - Feature engineering. Date field convert to year,month. Remove id, zipcode columns
        - Scale data and create tensorflow model
        - Train and Evaluate
        - Due to presence of outlier, can have a better model using bottom 99% price data
        
    Data - [DATA/cancer_classification.csv]

        - Read in data, perform EDA and visualize
        - Scale data and create tensorflow model
        - Model Overfits. Use EarlyStopping
        - Use Dropout layers along wiht EarlyStopping
        - Train and Evaluate
        - Model predicts with an accuracy of 98%