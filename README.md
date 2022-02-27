# Pet-Adoption-ML-Model

Problem

Problem Statement:  A leading pet adoption agency is planning to create a virtual tour experience for their customers showcasing all animals that are available in their shelter. To enable this tour experience, you are required to build a Machine Learning model that determines type and breed of the animal based on its physical attributes and other factors.

It is a multi-label or multi output classification problem.  
You have to predict two labels: 'breed_catagory' and 'pet_catagory'. Formally, multi-label classification is the approach of finding a model that maps inputs, x to binary vectors, y (assigning a value of 0 or 1 for each element (label) in y). 

How to solve it?? The best solution here is to train two models. Build one classification model and predict the output. Use the predicted output of 1st model as input feature to 2nd model. you can also try multi-class classification i.e., predicting both labels simultaneously, but it will give you poor score.
