# Hindi-Self-Supervised-ASR
    This repository attempts to build Hindi ASR system using transformers. The steps involved in fine tuning the Facebook developed pre-trained models are clearly mentioned. The steps can be followed to train ASR system in other language. Our trained Hindi Wav2Vec2 model is very accurate which is trained using varieties of open source data. However, for this demonstration, we show training using samples of commonvoice hindi data (https://commonvoice.mozilla.org/en/datasets). The model can be used to decode audio with or without language model. The steps are given in two different jupyter-notebook files.

# Installation 
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



# Reference:
Source code: https://github.com/pytorch/fairseq/blob/main/examples/wav2vec/README.md
