# capstone2
Spam classification



# Spam SMS classification
Spam SMS text messages are a nuisance and filtering them out to ensure that phone users are not distracted by unnecessary and annoying texts will enhance the customer's user experience.

This project seeks to build a NLP model to show how we can filter out such messages.
> Blog post with findings [_here_](https://medium.com/@andrewstothers/baywheels-smooth-ride-or-bumps-in-the-eef272a0ccf8). 

## Table of Contents
* [General Information](#general-information)
* [Technologies Used](#technologies-used)
* [Usage](#usage)
* [Files](#files)
* [Project Status](#project-status)
* [Summary of Results](#Summary-of-Results)
* [Room for Improvement](#room-for-improvement)



## General Information
The project uses data taken from Kaggle- it takes about 5500 messags from Singaporean students and has them marked as ham (genuine )or spam.

Data: https://www.kaggle.com/code/piroscotic/bda-project-spam-or-ham


We can use the content of the message to build an NLP model to determine whether a message is spam or not.



## Technologies Used
- Python - version 3.0
- Jupyter lab





## Usage
Download or link to the Capstone2.ipynb file and run in a suitable environment such as Jupyter lab or Zeppelin. It requires no extra software.


##Files
There are 3 files in the repository: this README, the  python notebook, and the data file mentioned above.


## Project Status
Project is: Complete


## Summary of Results
A model with 98% accuracy was built and could be used with success- some features such as the existence of a phone number or url were highly predictive


## Room for Improvement

Room for improvement:
- due to the version of SciKitLearn being deprecated, I was unable to determine which the top features were
- other models could have given better results such as Naive Bayes, Ada Boost etc.
- more hyperparameters could have been evaluated
- A larger dataset may be more helpful for further testing

## Sources of code

Where code was not known, it was sourced from Stack Overflow

