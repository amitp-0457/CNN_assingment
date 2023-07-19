# Project Name
To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

## Table of Contents
* [General Info](#general-information)
This assignment uses a dataset of about 2357 images of skin cancer types. The dataset contains 9 sub-directories in each train and test subdirectories. The 9 sub-directories contains the images of 9 skin cancer types respectively.



* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

- Finding on the first base model
The model is overfitting because we can also see difference in loss functions in training & test around the 10-11th epoch
The accuracy is just around 75-80% because there are enough features to remember the pattern.
But again, it's too early to comment on the overfitting & underfitting debate


-Finding from Second Model
There is no improvement in accuracy but we can definitely see the overfitting problem has solved due to data augmentation
We can increase the epochs to increase the accuracy so it's too early for judgement


- Which class has the least number of samples?
Answer-1 :- squamous cell carcinoma has least number of samples
- Which classes dominate the data in terms proportionate number of samples?
Answer-2:- actinic keratosis and dermatofibroma have proportionate number of classes.
melanoma and pigmented benign keratosis have proprtionate number of classes

-Todo: Analyze your results here. Did you get rid of underfitting/overfitting? Did class rebalance help?
Accuracy on training data has increased by using Augmentor library
Model is still overfitting
The problem of overfitting can be solved by add more layer,neurons or adding dropout layers.
The Model can be further improved by tuning the hyperparameter

* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Provide general information about your project here.
- What is the background of your project?
- What is the business probem that your project is trying to solve?
- What is the dataset that is being used?

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Conclusion 1 from the analysis
- Conclusion 2 from the analysis
- Conclusion 3 from the analysis
- Conclusion 4 from the analysis

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- library - version 1.0
- library - version 2.0
- library - version 3.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by...
- References if any...
- This project was based on [this tutorial](https://www.example.com).

## Git HUb link:
https://github.com/amitp-0457/CNN_assingment
