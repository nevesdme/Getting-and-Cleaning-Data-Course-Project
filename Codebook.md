# Codeboook for "Getting and Cleaning Data" Course Project

This is the codebook for this project. I'll quickly describe the variables, the data the transformations I did on the data as well.

The initial data for this project can be found [**in this website**](http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones#), it has many different variables but I'll only be describing the ones I used for this project.

### Variables

This dataset provides the following variables:

1. *subject* - ID of person
2. *activity* - ID of activity\
`1=walking     2=walking upstairs     3=walking downstairs     4=sitting     5=standing     6=laying`
3. From the 561 variables available in the original dataset I've only used the mean and standard deviation of the following features:
   - tBodyAcc-XYZ
