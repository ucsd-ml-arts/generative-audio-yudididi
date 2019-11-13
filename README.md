# Project 3 Melody of China

Yudi Wang, yuw043@ucsd.edu


## Abstract

Traditional Chinese music are quite different from the western classic music in many aspects. First, their theoretical basis is different. Western classical music is based on twelve temperament, and China is "Gong Shang Jue Zhi Yu". Second, Chinese folk music instrument are designed to perform solo and have clear characteristic, whereas many western and brass instrument are designed to perform together. Thus, third point is, Chinese music care about the pursuit of nature, artistic conception and emotional experience, and its form has been very simple, mainly single melody. 

In this project, I use the LSTM algorithm to generate traditional chinese melodySince the dataset is quite large, I make adjustment of the batch size from 64 to 256, which reach a balance before spped and RAM. After 40 iterations, the loss become 0.7, which is a suitable value to create some new melody. Sample pieces are generated and we can clear figure out the three above mentioned characteristics from these samples. Finally, I try to combine these generated piece with piano, drummer's performance to create some music work, which are a popular way to let the old art rejuvenate.



## Model/Data


- LSTM model to train and generate samples
- Data https://kern.humdrum.org/cgi-bin/browse?l=/essen/asia/china


## Code

- Jupyter notebooks: LSTM_ChineseMusic.ipynb

## Results

Folder: *Generated Sample*, including 16 sample pieces generated by algorithm(.midi documents).



## Technical Notes

Need to pip another packages: *music21*, glob, pickle, keras
 
This project need to run on Colab to use GPU resources, google.colab package and Google Drive


## Reference

Refer to *Music generation with LSTM in Keras* offered by Google

https://colab.research.google.com/drive/19TQqekOlnOSW36VCL8CPVEQKBBukmaEQ
