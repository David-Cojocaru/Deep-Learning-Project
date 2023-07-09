# Deep-Learning-Project

<h1 align="center">
  <br>
Amazon Book User Review Score Predictor
  <br>

## Preparing The Nessecery Files
To run this notebook, you first need to download a pre-trained model and a .json file.
Once you have all the files, you may want to configurate the file paths to match those written in the notebook

### Pre-Trained Model Checkpoints
You can download one of the checkpoints from here:

- Pre-Trained BERT classifier model: https://drive.google.com/file/d/1dsr0WPp24lZe9ZiVba35AXrSCQPayiL5/view?usp=drive_link
- Pre-Trained Fine-Tuned classifier model: https://drive.google.com/file/d/1S7ym7tiG9lTkD_eRb_I3kJn2OWhaLlNu/view?usp=drive_link

The first option is the model we used as a base for training, and the second is the model after fine-tuning done during the traning phase (about 100k samples)

### Kaggle json file
To access the dataset, instead of downloading 3M samples, we source our dataset from kaggle.
To do that, you are required to get a kaggle.json file, here is how to do it:

- Go to your kaggle account, Scroll to API section and Click Expire API Token to remove previous tokens
- Click on Create New API Token - It will download kaggle.json file on your machine.
