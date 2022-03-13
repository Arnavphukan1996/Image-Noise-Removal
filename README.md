### Aim:
To remove the noise from the given images of MNIST Dataset.
### About the dataset:
The dataset has been taken from kaggle. The MNIST Dataset is having train.csv and test.csv as separate files. 
Number of Rows: 70,000
Number of Columns: 784
Link to the [dataset](https://www.kaggle.com/c/digit-recognizer/data)
### Objective:
To convert all noisy images to clear images with the help of knn algorithm.
### Steps of conversion:
1. Add artificial noise.
2. Perform random sampling.
3. Reshape to gray scale ie 28x28 pixels.
4. Resize the image to fit the output window.
5. Reshaping back to 784 pixels.
### Methods used:
1. copyMakeBorder()
2. cvtColor()
3. putText()
### Tools and Technology:
- Language: Python
- IDE: Jupyter Lab
- Files: train.csv and test.csv
### Conclusion
Converted all noisy images to de-noise images.
