# Sentiment Analysis Web App Using PyTorch and SageMaker :clapper:
Creating a Sentiment Analysis Web App Using PyTorch and SageMaker

# Project Overview:
This project is the final project of Deep Learning program of Udacity. In this project I used SegaMaker to construct the project from beginning to end. I developed a simple website which take a user review on movie as input then predict which is positive or negative review by send the review to my model which will predict the sentiment of the entered review.

![Screen%20Shot%202019-07-09%20at%204.02.18%20PM.png](attachment:Screen%20Shot%202019-07-09%20at%204.02.18%20PM.png)

# Project Instructions:
## Instruction
1. Clone the repository and navigate to the downloaded folder.
```
git clone https://github.com/iSarah-alsh/Sentiment-Analysis-Web-App-Using-PyTorch-and-SageMaker.git
```
2. Open the SageMaker Project.ipynb file. Of course, you can find HTML version of the file.
```
jupyter notebook SageMaker Proejct.ipynb
```
3. Read and follow the instructions! You can find and download the dataset for this project in the notebook.

# Project Information:
## Contents 
- General Outline
- Step 1: Downloading the data
- Step 2: Preparing and Processing the data
- Step 3: Upload the data to S3
- Step 4: Build and Train the PyTorch Model
- Step 5: Testing the Model
- Step 6: Deploying the model for testing
- Step 7: Use the model for testing
- Step 6 (again): Deploy the model for the web app
- Step 7 (again): Use the model for the web app

# Libraries:
The list below represents main libraries and its objects for the project.

- Amazon SageMaker (Build, train, and deploy a model)
- PyTorch (LSTM classifier)

# Delete the Endpoint
Remember to always **SHUT DOWN YOUR ENDPOINT** if you are no longer using it. You are charged for the length of time that the endpoint is running so if you forget and leave it on you could end up with an unexpectedly large bill !

```
	predictor.delete_endpoint()
```
