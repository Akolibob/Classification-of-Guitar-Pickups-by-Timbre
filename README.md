# Classification-of-Guitar-Pickups-by-Timbre

This is a project that I started for my undergraduate coursework that I am actively developing to create a usable and comprehensive algorithm for classification of electric guitar pickups by timbre.

## What is the project?

The code is devided by sections:
  - File Import
  - Feature Extraction of Audio Files
  - Machine learning model training (currently using kNN)
  - Evaluation of features and model and re-training

The code is made in a way that only certain sections of it can be used. Read the TO-DO list for more information.

# How can I use the code?

The goal of this project was initially a way to identify the sound of a guitar pickup and categorize it so the buyer can find something that is matching the tone they want. Even though guitar pickups have a much smaller effect on the timbre compared to the rest of the electronics in a guitar, it is something that can help the buyer make a more informed decision with more information. 

What is lacking from this project is a proper dataset which, if someone was to use the same electronics and setup, and properly record sound files with only the pickup as a variable, it woul help the evaluation of the impact of pickups in the sound profile of the electric guitar. 

## TO-DO List:
  - Make functions for repeating sections
  - Make seperate files for each function
  - Take the type of the pickup into account
  - Improve the training to adjust the number of features used
  - Use more ways to evaluate the accuracy of the algorithm
  - Write more comprehensive comments explaining the code
