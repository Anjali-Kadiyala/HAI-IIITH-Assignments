# Assignment-2 submission to Healthcare and AI (HAI) at IIIT-Hyderabad.

## Reimplementation of the paper [MINA: Multilevel Knowledge-Guided Attention for Modelling Electrocardiography Signals](https://arxiv.org/pdf/1905.11333.pdf)

The authors of the paper are Shenda Hong, Cao Xiao, Tengfei Ma, Hongyan Li, and Jimeng Sun

### Usage

In order to implement the code, open the location of the code in the terminal and run the following command.
> python main.py

### Dataset

The dataset is the training data of the [PhysioNet Challenge 2017](https://archive.physionet.org/challenge/2017/). It can be found [here](https://archive.physionet.org/challenge/2017/#challenge-data)

Labels to this training dataset have been revised thrice. The most latest labels can be found [here](https://archive.physionet.org/challenge/2017/REFERENCE-v3.csv)

The original authors were kind enough to provide the [preprocessed data, challenge2017.pkl](https://drive.google.com/drive/folders/1AuPxvGoyUbKcVaFmeyt3xsqj6ucWZezf), which can directly be used in the reimplementation.
However, code for preprocessing is provided in the util.py file. 

### Environment

 Python 3.8.10
 torch 1.9.0
 tqdm  4.61.1
 scikit-learn 0.24.2    
 scipy 1.7.0
 numpy 1.20.3
 pandas 1.2.5
 matplotlib 3.3.4
 
 #### Detailed report can be found [here](https://github.com/Anjali-Kadiyala/HAI-IIITH-Assignments/blob/main/HAI-Assignment-2/Report_Anjali.pdf)
