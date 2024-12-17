# DataMiningFinal_EEG
by: Shalin Thomas

The objective of this project is to classify Electroencephalography (EEG) data collected during a brain activity experiment into three distinct conditions: consistent, misleading, and control. 

**Step 1: Data Preparation**

1. Import the base and peak CSV files and remove columns containing the string "Fp1_"
2. Combine base and peak data files into a single dataset and remove columns containing null values
3. Structure and combine data based on class 'consistent', 'misleading' and 'control' and add 'class' column (Target)
4. Plot the distribution of the target values to visualize the class balance.


**Step 2: Pre-processing**

1. Remove any outliers from the dataset.
2. Apply one-hot encoding to the time window columns.
3. Split the data into feature set (X) and target set (y) for training and testing.
3. Apply Min-Max scaling to normalize node values
4. Perform feature selection to reduce dimensionality and keep the most relevant features.

**Step 3: Building the Model**
1. Decision Tree
2. RandomForrest
3. Neural Networks
4. Naive Bayes

**Step 4: Evaluation**
1. Evaluate the model performance using the ROC curve to assess classification quality
