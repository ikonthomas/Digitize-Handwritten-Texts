# Digitize-Handwritten-Texts
 I will tackle the issue of handwritten scribes usually written by Doctors and Nurses. In my project I will digitize handwritten scripts to digital records which can then be stored in non relational databases.   The data used to build the model was collected from IAM Handwriting database. This model is built on handwriting from 657 different writers. Each writer has written multiple paragraphs and sentences have been extracted from those paragraphs.

# Model#

I have built a multi layer CNN in Keras to classify writers followed by RNN in tensorflow. The inspiration for this work comes from a paper written by Alex Graves referenced below. They were able to successfully classify and read English text. I have taken some key concepts from the paper and modified the neural network for this task

# Results

Model's performance has been calculated based on a test set which has writings from among 50 writers. The model was not exposed to this data during training and validation Classification accuracy on Test Set : 94.1%

# Resources

IAM handwriting database http://www.fki.inf.unibe.ch/databases/iam-handwriting-database/download-the-iam-handwriting-database
Alex Graves work on RNN https://arxiv.org/pdf/1308.0850.pdf
