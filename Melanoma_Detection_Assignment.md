# Melanoma Detection Assignment

1. Data pipeline

1.1 Data reading

You have defined the paths for both train & test images correctly. . . . .

1.2 Dataloader

You have correctly created train & validataion dataset from the train directory created earlier. While creating the batch size is 32 and it has resized to 180*180.

1.3 Data visualisation

You have visualized one instance of all the nine classes present in the dataset . . . . . . .

1.4 Augmentation

You have identified the issue of overfitting in the model training and has correctly applied an augmentation strategy to add more images to the entire training dataset

1.5 Class Distribution

You have shown the class distribution of the training dataset and has correctly identfied - Which class has the least number of samples? - Which classes dominate the data in terms of the proportionate number of samples?

1.6 Class imbalance handling

You have correctly implemented the starter codes to add 500 images to each class using Augmentor library.


2. Model Building


2.1 Model building on raw dataset

You have accurately trained a CNN model on the original training dataset. which are normalized to values between (0,1). You have written your findings.

2.2 Model building on augmented dataset

You have accurately trained a CNN model using dropout layer on the original training dataset, which are normalized to values between (0,1). you have writen your findings.

2.3 Model building on rectified dataset

You have accurately trained a CNN model using dropout layer on the original training dataset. which are normalized to values between (0,1). You have written your findings after the model fit .


3. Coding Guidelines


3.1 Coding Guidelines - Good Practices

there is a GitHub repository link containing a python file and a README.md file. And README.md file contains a brief description of the project.
