# ML Final Project
Machine Learning (NTU Course 2019 Fall)

## Summary
**Dialogue Modeling**, more specifically, is a multi-turn response selection task from [Dialog System Technology Challenges 7 (DSTC7).](http://workshop.colips.org/dstc7/call.html)

This challenge provides a partial conversation, and requires participants to select the correct next utterances from a set of candidates. Unlike previous similar challenges, this task tries to push towards real world problems by introducing:
- A large number of candidates
- Cases where no candidate is correct
- External data

In this project I try to reproduce the model proposed by 
[Chen and Wang (2019)](https://arxiv.org/pdf/1901.02609.pdf).

## Dataset
![](https://i.imgur.com/f7q2Fkr.png)

Given a multi-turn conversation, choose a correct response from a pool (at least 100 candidate sentences.)

## Model 
![](https://i.imgur.com/Zmvl8Mz.png)

The proposed model **Enhanced Sequential Inference Model (ESIM)** is inspired by [Chen et al. (2017)](https://www.aclweb.org/anthology/P17-1152/), including the following modules:
- Input encoding 
- Local matching
- Matching composition


## Reference
- [Sequential Attention-based Network for Noetic End-to-End Response Selection (2019)](https://arxiv.org/pdf/1901.02609.pdf)
- [Enhanced LSTM for Natural Language Inference (ACL-17)](https://www.aclweb.org/anthology/P17-1152/)

## Contact
If you have any question, please feel free to contact me by sending email to [r08946014@ntu.edu.tw](mailto:r08946014@ntu.edu.tw)