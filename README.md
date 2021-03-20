# Neural_Network_Charity_Analysis

## Overview of the analysis: 

In this challenge, we used our knowledge of neural networks and machine learning to help predict the Alphabet Soup charity and if applicants are more successful if funded by it. With the given dataset, I was able tto use features within it to create a binary classifier capabale of predicting. The three main deliverables included preprocessing the data for the model, compiling, training and then evalauting the model, and lastly, optimizing the model. Our original CSV file contained over 34,000 organizations that have received funds over the years from Alphabet Soup. This also includes columns as a mechanism to capture metadata about each individual oragnaization. 

## Results: Using bulleted lists and images to support your answers, address the following questions.

### Data Preprocessing

* My target variable for my modle is "IS_SUCCESSFUL". 
<img width="563" alt="Screen Shot 2021-03-20 at 5 34 29 PM" src="https://user-images.githubusercontent.com/71396367/111886172-9a37fd80-89a2-11eb-98ad-5203631357db.png">

* Because "IS_SUCCESSFUL" is our target variable, all other columns are considered the variables to be featured.

* Variables that we dropped that are neither targets or features are "EIN" and "NAME". 
<img width="532" alt="Screen Shot 2021-03-20 at 5 38 17 PM" src="https://user-images.githubusercontent.com/71396367/111886243-103c6480-89a3-11eb-8ce9-ed976f2ff88b.png">

### Compiling, Training, and Evaluating the Model

* For my first attempt, I used 8 and 5 nuerons with 2 layers and and output layer. 

<img width="903" alt="Screen Shot 2021-03-20 at 5 43 49 PM" src="https://user-images.githubusercontent.com/71396367/111886434-d586fc00-89a3-11eb-9cb6-beb9d6d25af1.png">

* In my second attempt, I changed up how many neurons I was using to 10, 5 and 3, then added 3 layers with an output layer. 

<img width="891" alt="Screen Shot 2021-03-20 at 5 49 56 PM" src="https://user-images.githubusercontent.com/71396367/111886539-b177ea80-89a4-11eb-8f28-be26b1aa3110.png">

* Lastly, one the third attempt, I decided to keep it some what similar to the second attempt but took the layers down to two and kept 10 and 5 neurons. 

<img width="885" alt="Screen Shot 2021-03-20 at 5 51 14 PM" src="https://user-images.githubusercontent.com/71396367/111886559-dec49880-89a4-11eb-8135-a59e287c8980.png">

* With all three of my attempts I never was able to achieve the target performance for the model. 
  * First Attempt:
<img width="477" alt="Screen Shot 2021-03-20 at 6 14 01 PM" src="https://user-images.githubusercontent.com/71396367/111886935-0d903e00-89a8-11eb-92eb-225214312443.png">

  * Second Attempt:
<img width="472" alt="Screen Shot 2021-03-20 at 5 54 54 PM" src="https://user-images.githubusercontent.com/71396367/111886611-61e5ee80-89a5-11eb-891a-b8eccb0695b3.png">

  * Third Attempt:
<img width="465" alt="Screen Shot 2021-03-20 at 5 55 30 PM" src="https://user-images.githubusercontent.com/71396367/111886620-775b1880-89a5-11eb-993f-fa4d6380fddd.png">

* In all three attemps, I tried using a different amount of layers and neurons in order to try and hit the target peformance for my model but was not able too. 

## Summary: 
In summary, it appears my second and third attempt had a better acurracy overall then my first attempt with a 72%. Possibly the reason it ws not working is that I did not have enough layers or possibly neurons. If I had attempted to add more, would it have achieved a better accuracy score? I recommend trying the Random Forest for the classification issue. 
