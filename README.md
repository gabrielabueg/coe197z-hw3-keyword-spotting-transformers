# Keyword Spotting Using Transformers
Homework 3 submission for CoE197Z\
John Gabriel Porton  \
201803016

## Link/Reference
This homework is based on: \
[KWS-demo](https://github.com/roatienza/Deep-Learning-Experiments/blob/master/versions/2022/supervised/python/kws_demo.ipynb)\
[KWS-infer](https://github.com/roatienza/Deep-Learning-Experiments/blob/master/versions/2022/supervised/python/kws-infer.py)\
[Transformer Demo](https://github.com/roatienza/Deep-Learning-Experiments/blob/master/versions/2022/transformer/python/transformer_demo.ipynb)

  
## Prerequisite/Setup
1. Clone the repository
2. Download necessary libraries/modules/packages using `pip install -r requirements.txt` \
  
## Code Execution

    `python train.py` for training\
    `python kws-infer.py --gui` if doing real time inference on a gui\
    
## Outputs and Graphs

The training is done on Google Colab, and the model is able to reach 88.4% accuracy with a test loss of 0.467 at Epoch 15, 
before google colab gpu runtime has expired. 

The demo app is gui-based and can recognize keywords from the PCs mic. Terminates if the keyword recognized is 'stop' \





