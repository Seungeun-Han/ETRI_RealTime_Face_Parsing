# ETRI_RealTime_Face_Parsing
 This is a description of the face parsing model developed by Seungeun Han at ETRI from July 2022 to the present.

The intellectual property rights of all software belong to ETRI. 

Therefore, I cannot share the training code. If you need more assistance, please contact hse@etri.re.kr.

<img width="706" alt="4" align="center" src="https://github.com/Seungeun-Han/ETRI_RealTime_Face_Parsing/assets/101082685/7c9e3fc2-1bc9-4e1c-945b-a352f4be095a">


<br>

## Table of Contents
- [Requirements](Requirements)
- [Data](#data)
- [Inference](#inference)
- [Results](#results)
- [Authors](#authors)

<br>

## Requirements

Our model is based on Pytorch 1.7.1 with Python 3.8.

Install the other requirements by

```
pip install -r requirements.txt
```

<br>

## Data

You can download original datasets:

- Helen : https://www.sifeiliu.net/face-parsing
- LaPa : https://github.com/JDAI-CV/lapa-dataset
- CelebAMask-HQ : https://github.com/switchablenorms/CelebAMask-HQ

and put them in ./dataset folder as below

```
dataset/
    images/
    labels/
    edges/
    train_list.txt
    test_list.txt
        each line: 'images/100032540_1.jpg labels/100032540_1.png'
```

If you have to make parsing and edge label, please refer to the following link [Preprocessing](https://github.com/Seungeun-Han/Face-Parsing-Preprocessing).

There are several pre-precessing codes for face parsing.


<br>



## Authors

한승은 &nbsp;&nbsp;&nbsp;  hse@etri.re.kr

