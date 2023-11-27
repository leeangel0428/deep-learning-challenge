# Introduction

Hello viewer and welcome to my submission for Challenge 21 aka the deep-learning-challenge. For context, at the time of writing this, I am enrolled in the Data Analytics and Visualizations bootcamp with the University of MN. We are assigned a challenge homework per module. This is Module 21's challenge on neural networks and deep learning. I am using a windows/PC laptop.

# Overview

Challenge: Use features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup (fictional non-profit foundation needing a tool that can help it select applicants for funding with best changes of success).

### Additional information

This challenge consists of 5 parts: 
- Step 1: Preprocess the Data
- Step 2: Compile, Train, and Evaluate the Model
- Step 3: Optimize the Model
- Step 4: Write a Report on the Neural Network Model
- Step 5: Copy Files into Your Repository

### Repository Structure
In this repository, you will find the Starter_Code folder that contains the Starter_Code file with an incomplete template. You will also find my initial completed file called AlphabetSoupCharity, my optimization attempt called AlphabetSoupCharity_Op, the Report, the screenshot results, and the response ChatGPT gave me when I asked how to save the models.

# Results

I initially tried 8 hidden nodes in layer 1 and 3 hidden nodes in layer 2 with 100 epochs:

![8-3-100](https://github.com/leeangel0428/credit-risk-classification/assets/137225965/bc066db4-e868-48bd-811f-b96f2f54e812)

I then tried 8 hidden nodes in layer 1 and 5 hidden nodes in layer 2 with 100 epochs: (This was the one I saved as the AlphabetSoupCharity file)

![8-5-100](https://github.com/leeangel0428/credit-risk-classification/assets/137225965/e808a381-ad30-4608-8904-45d9b28aca43)

Last I tried 8 hidden nodes in layer 1 and 5 hidden nodes in layer 2 with 200 epochs: 

![8-5-200](https://github.com/leeangel0428/credit-risk-classification/assets/137225965/ad8e5894-cadd-437d-9788-a66d4b2b231f)

**Unfortunately, I was unable to hit the target accuracy of 75%.** My best attempt was my second attempt with an accuracy of 73%.


# Troubleshooting:

I wasn't sure how to properly save the model so I asked ChatGPT for a suggestion. I tweaked the example so it would work but I do not think it did because no results were saved. I instead had to screenshot the results.

![chatgpt_saving_nn](https://github.com/leeangel0428/credit-risk-classification/assets/137225965/af52478b-ca8a-45c2-bcda-bbbc5a38cdbe)


# Resources
Aside from using ChatGPT to find out how to save the model, everything used was retained information gathered from my classes and class activities. As always shout out to my bootcamp TAs Sam and Randy for all their help answering my questions during office hours, my instructor Hunter for always being clear in his articulation of the course material, and my classmates for their encouragement and support.
