
## Music Generation Using Deep Learning

The use of Deep Learning techniques to solve problems in the field of literary arts has gained recent interest among researchers. Generating musical content that is both- pleasant to hear and obeys the rules and structure of music theory is the biggest challenge. The ulterior motive of this task is to enhance the creativity of an artist and produce new compositions that are similar in style and dynamics to an original artist.  In this project, we attempt to translate the task of music generation to a language modelling problem. We apply the ‘bag-of-frames’ approach and vector quantize the log mel-spectrograms of raw audio files into a vector of ‘symbols’ that can now be interpreted as a language sequence. 


![image1.png](attachment:image.png)

## Approach

![appraoch.png](attachment:Picture1%20%283%29.png)

## Setup

<b>Requirements</b>
    - Python 3.7
    - Jupyter Notebooks
    
<b>Instructions</b>
- Download Bert_generation.ipynb and open using jupyter notebook. 
- Install Pytorch Pretained BERT model
- Download codebook and Vector quantized CSV files
- Run the jupyter notebook by providing initial two or three sequences


## References

- Jacob Devlin, Ming-Wei Chang, Kenton Lee, Kristina Toutanova, Google AI Language; BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding, 2018

- Makhoul, John, Salim Roucos, and Herbert Gish. "Vector quantization in speech coding." Proceedings of the IEEE 73.11 (1985): 1551-1588

