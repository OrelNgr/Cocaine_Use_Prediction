# Cocaine_Use_Prediction
Prediction of coke use based on "the big five" using ML & DL
---------------------

## Introduction
This is a prediction for coke use based on basic charactaristics (gender, age etc...) and "the big five" score of the user.
To date, over a million Americans are addicted to cocaine - one of the most addictive substances that is considered very difficult to treat. In Israel, and especially in Tel Aviv, cocaine use is very common. Israel is ranked 20th in the world in the amount of cocaine use, in relation to the size of the population.
Also, in psychology, a person's personality is described through the 'five great qualities' that have a significant effect on him, which are: Extraversion, Agreeableness, Conscientiousness, Emotional-Neuroticism and Openness to experience.
In this project, we are interested in examining the relationship between the 'five major traits' as well as other variables (gender, age, ethnicity, education, etc.), and cocaine use - use / not use. The project can be used as an aid to security / public institutions in that it can verify the past of the candidates being examined for relevant positions. This project is an applied project - we expect that many institutions will be able to use this tool, and will see it as a useful tool for early identification of candidates who are not suitable for the institution.

## Requirements
json
json5==0.9.1
pandas==1.0.1
numpy==1.18.1
pprint
gradio==2.9.4
PercentFormatter
seaborn==0.10.0
sklearn
matplotlib==3.5.1
collections
sortedcollections==1.2.1
itertools

## Installation
Only pip install all the needed libraries in the requirements above.

## Configuration
we choose to run the ANN model, if you want to test the Gradio with a different model, such as Random Forest or Adaboost  which were also impleneted in this code just change the model that is in use of the Gradio function at the end of the notebook.

## Troubleshooting
If the Gradio does not display, check if:
1. You did installed the pip correctly
2. You are connected to the internet

## FAQ
Q: How did you do such a great project? this is just over the top...
A: We are awesome we know. This was all possible due to Chen, our leacturer.

 * Maintainers
Current maintainers:
 - Orel Nagar- OrelNgr@gmail.com
 - Or Ben-Tovim - orbentovim11200@gmail.com
 - Noa Mor - noaMor1994@gmail.com
