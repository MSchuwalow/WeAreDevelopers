# weAreDevelopers 2017

This repository contains code for the WeAreDevelopers conference 2017

In the notebook directory you'll find the notebook that we used to generate our visualisations and a guided example for implementing a Text-CNN.

## Setup
If you want to modify and run the notebooks yourself, you'll need to set up a few things first.

- First you'll need to download and extract the pretrained Word Embeddings (Word2Vec) from [here] (https://drive.google.com/uc?id=0B7XkCwpI5KDYNlNUTTlSS21pQmM&export=download). Then the file has to be moved into the resources folder.
First download the file and then run:
'''
gunzip *.gz
mv *.bin $NOTEBOOK_LOCATION/resources 
'''

- Second you'll need to install the requirements with pip3
'''
pip install -r requirements.txt
'''

