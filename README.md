# Train a speech-to-text model using Watson Studio 

IBM provides state of the art speech to text service conversion service. We will look at how to extend this service to custom domain model using transfer learning by training the existing AI model with new data in your domain. This hands-on workshop will walk you through a number of steps including

1. Prepare audio and transcription data for training the Watson model.

2. Use the Watson Speech to Text API to train on the new data.

3. Deploy the new model on IBM Cloud and learn how to use it with the API in your custom application

Pre-requisites - Curious minds and your laptop to program on! Beginner developers are welcome!

## Presentation and workshop
[Slides](https://slides.com/upkar/ibm-nlp) - https://slides.com/upkar/ibm-nlp
## Data for classifier
1. [complete file](data/spam-ham-data.csv)
2. [ham training](data/ham-train.csv)
3. [ham test](data/ham-test.csv)
4. [spam training](data/spam-train.csv)
5. [spam training](data/spam-test.csv)

## Notebook to test classifier
[ham-spam notebook](notebook/ham-spam.ipynb)
## Sample Applications
1. [Job Classifier](http://nlc-job-descriptions.mybluemix.net/#)
2. [Natural Language Understanding](https://natural-language-understanding-demo.ng.bluemix.net/)
3. [Email “Phishing,” “Spam,” or “Ham”](https://developer.ibm.com/patterns/predict-phishing-attempts-in-email-with-nlc/)

## Speaker
Upkar Lidder is a Full Stack Developer and Data Wrangler with a decade of development experience in a variety of roles. He can be seen speaking at various conferences and participating in local tech groups and meetups. Upkar went to graduate school in Canada and currently resides in the United States.