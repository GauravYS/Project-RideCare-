
# Hi, I'm Gaurav! 👋


## 🚀 About Me
I'm a machine Learning enthusiast . My areas of interest are Deep Learning and it's applications , Artificial Intelligence for Autonomous vehicles , Natural Language Processing and generative AI.

# RideCare


This project aims to tackle the issue of rider safety in ride hailing servives like lyft and uber. The main idea behind this project is toxic comment classification and then analyzing the severity associated to these comments and raising an alert accordingly via Twilio. This involves utilizing speech to text and analyzing this text using machine learning models.


## Additonal Information 

This project uses different pre-trained models to achieve state-of-the-art accuracy in classification of the comments.The models used are DistilBERT and RoBERTa. 
## Dataset description 

The dataset used in this project is the hand-labelled 'Toxic Comment Classification' data used to train Google's Perspective API. It is originally a multi-class classification problem with 6 labels - toxic , severe_toxic , obscene, threat , insult and identity hate which has been converted to a single-label binary classification problem using this formula :

**Score = 0.7*P(toxic) + 0.5*P(obscene)+P(threat)+0.8P(insult)+P(identity_hate)+P(severe_toxic)**
## System Architecture 

![](https://github.com/GauravYS/Project-RideCare-/assets/116845183/5a00f649-d85e-4743-801d-2dae4eca1779)



## Installation

Install the requirements.txt 

```bash
  !pip install transformers
```

## Software Requirements 

1)Python-3

2)Vosk for speech to text conversion 

3)Perspective API

4)Twilio for sending SMS to emergency contacts

## Hardware requirements for the complete implementation

  1)Raspberry Pi Model 4 B

  2)Blue Yeti Nano USB microphone
## Authors

- [@GauravYS](https://github.com/GauravYS)

