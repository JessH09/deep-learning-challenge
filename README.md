# deep-learning-challenge
Challenge 21
Background
The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. With your knowledge of machine learning and neural networks, you’ll use the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.

From Alphabet Soup’s business team, you have received a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years.

Analysis
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Overview of the analysis: The model's purpose is to predict which applicants will be successful so Alphabet Soup can better select applicants for funding.

Results:

Data Preprocessing

What variable(s) are the target(s) for your model?

target variable was whether or not a project was successful What variable(s) are the features for your model?
feature variables was everything else What variable(s) should be removed from the input data because they are neither targets nor features?
EIN and Name were removed as they are neither target or features
Compiling, Training, and Evaluating the Model

How many neurons, layers, and activation functions did you select for your neural network model, and why?
Attempt 1:
![Screenshot 2024-05-14 215531](https://github.com/JessH09/deep-learning-challenge/assets/152633475/f39af477-24aa-4946-a405-f70be2900cb2)

Attempt 2: 
![Screenshot 2024-05-14 215548](https://github.com/JessH09/deep-learning-challenge/assets/152633475/4d0a3a31-4899-4519-9c61-8846984b5d56)

Attempt 3:
![Screenshot 2024-05-14 215602](https://github.com/JessH09/deep-learning-challenge/assets/152633475/36e63ce0-5f32-4fad-8ef3-5874ff8c6b3d)

At first I chose 2 hidden layers since that is what we worked with during the data pre-processing, then I upped it to 3 to see if this will give better optimization. Were you able to achieve the target model performance?
No What steps did you take in your attempts to increase model performance?
adding in another layer, increasing/decreasing the number of hidden nodes, changing the number of epochs
Summary: Overall the model that I used was not successful in optimization. The first model was closest with an accuracy of 73% which tells me that adding more layers and epochs does not increase the accuracy in this model.Future recommendations is to adjust data and see if the data that is being fed into model changes accuracy.
