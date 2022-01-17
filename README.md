# Hindi-Self-Supervised-ASR

This repository attempts to build Hindi ASR system using transformers. The steps involved in fine tuning the Facebook developed pre-trained models are mentioned, and can be followed to train ASR system in other language. For this demonstration, we show training using samples of commonvoice hindi data (https://commonvoice.mozilla.org/en/datasets). The trained model can be used to decode test audio with or without language model. 

## Installation 
    1. Install python package (To train and evaluate the model)
    ===========================================================
    pip install transformers
    pip install datasets
    pip install torch
    pip install jiwer



    2. Install kenlm (To train the language model)
    ===============================================
    git clone https://github.com/kpu/kenlm.git 
    cd kenlm
    mkdir -p build && cd build
    cmake ..
    make -j 4
    cd ../..


<-Readme updation under processing->



## Reference:
Source code: 
1. https://huggingface.co/blog/fine-tune-wav2vec2-english 
2. https://github.com/pytorch/fairseq/blob/main/examples/wav2vec/README.md
