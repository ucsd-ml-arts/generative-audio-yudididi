# Project 3 Melody of China

Yudi Wang, yuw043@ucsd.edu


## Abstract

Traditional chinese music are quite different from the western classic music by both the instruments and the rhythm. Nowadays young people in China feel that music contains traditional chinese element are extremely attractive. In this project, I'll use the GANSynth algorithm to generate traditional chinese country melody. The biggest obstacle should be the collection of dataset. Since I'd like to generate long piece, training based on the midi dataset should be better. However, there exists no suitable chinese traditional midi dataset that we can directly use. Thus, first I will use python scrapy package to grasp the midi dataset from the related website, then we will try three method: 1)use CNN+LSTM; 2)Use GANSynth; 3) Use wavegan; to generate music.

## Model/Data

Data 

https://github.com/lukewys/Guqin-Dataset#%E5%8F%A4%E7%90%B4%E6%95%B0%E6%8D%AE%E9%9B%86

https://kern.humdrum.org/cgi-bin/browse?l=essen/asia/china/han

Briefly describe the files that are included with your repository:
- trained models
- training data (or link to training data)

## Code

Your code for generating your project:
- Python: generative_code.py
- Jupyter notebooks: generative_code.ipynb

## Results

Documentation of your results in an appropriate format, both links to files and a brief description of their contents:
- `.wav` files or `.mp4`
- `.midi` files
- musical scores
- ... some other form

## Technical Notes

Any implementation details or notes we need to repeat your work. 
- Does this code require other pip packages, software, etc?

https://github.com/humdrum-tools/humdrum-data

- Does it run on some other (non-datahub) platform? (CoLab, etc.)

## Reference

References to any papers, techniques, repositories you used:
- Papers
- Repositories
- Blog posts
