# Parameter_Optimization_of_SVM

Dataset Used: [Occupancy_estimation](https://archive.ics.uci.edu/ml/machine-learning-databases/00640/)

| No. of Instances: | 10129 |
| :---:             |:---:  |
| No. of Attributes:|19     |


# Tasks performed
1. Downloading the dataset from UCI library
2. Preprocessing the dataset
3. Creating 10 samples after Split the samples in 70 : 30 for training and testing
4. Optimising SVM using randomisation for every sample and report best accuracy and best parameters
5. Plotting the convergence graph For the best sample

# Result

| Sample | Accuracy | C   | Gamma  | Kernel |
| :---:  | :---:    |:---:| :---:  | :---:  |
| 1      | 0.99440  |0.615|0.0051  |rbf     |
| 2      | 0.99243  |0.982|0.032   |rbf     |
| 3      | 0.99111  |0.590|0.0393  |rbf     |
| 4      | 0.99539  |0.754|0.0129  |rbf     |
| 5      | 0.99605  |0.749|0.0011  |rbf     |
| 6      | 0.99769  |0.419|0.0020  |rbf     |
| 7      | 0.98321  |0.593|0.0576  |rbf     |
| 8      | 0.99276  |0.703|0.0388  |rbf     |
| 9      | 0.98321  |0.727|0.0552  |rbf     |
| 10     | 0.99341  |0.901|0.0290  |rbf     |

# Convergence Graph

<img width="428" alt="image" src="https://user-images.githubusercontent.com/111454531/233119542-86800c43-eb9c-40f1-b0f6-cc9386cbaeeb.png">

