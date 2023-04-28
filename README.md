# Terrain Identification from Time Series Data

Team 110 - Ashwini Muralidharan, Vaidehi Koppolu, Shahil Manoj Dhotre

Functions to run for training model

Step 1: Import all the packages
Step 2: run cells defining get_mode(), preprocess(), train_test_val_split(), and encoder()
Step 3: Estimate class weights
Step 4: run cell defining evaluation metrics: recall(), precision(), f1()
**Step 5: define bidirectional_lstm() and run all the cells related to models till model.fit()**
Step 6: Plot graphs to check train and valid loss and accuracy

Functions to run for prediction
Step 1: define functions to convert test data into the format of the data used while training: test_preprocess(), get_mode()
Step 2: load test files
Step 3: Run last cell of the file to generate prediction and save in csv format
