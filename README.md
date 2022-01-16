# Hindi-Self-Supervised-ASR
    This repository attempts to build an accurate hindi speech recognition model. 


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
