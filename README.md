# Emotion recognition scoreboard
An attempt at tracking state-of-the-arts in emotion recognition. 

### Note
Evaluation results are taken directly from their respective sources.
No attempt has been made to verify conformity in definition or calculation of the named metrics. 
It should also be noted that while the results are separated based on cross-validation method, there is no unison on the number of total samples or validation data/method used for final model selection.
The categories of targeted emotions may also differ. 

## IEMOCAP
### 10-fold cross validation
| UA | WA | F1 | Model | Paper | Modality | Year | Code |  Notes   |
| :-: | :-: | :-: | :-:  | :-: | :-:  | :-:  | :-:  | :-: |
| 61.7 | 64.5 | - | CNN+LSTM | [CNN+LSTM Architecture for Speech Emotion Recognition with Data Augmentation](https://arxiv.org/pdf/1802.05630v2.pdf) | Audio | 2019 | - | - |

### 5-fold cross validation
| UA | WA | F1 | Model | Paper | Modality | Year | Code |  Notes   |
| :-: | :-: | :-: | :-:  | :-: | :-:  | :-:  | :-:  | :-: |
|  - |  71.8 | - | RNN | [Multimodal Speech Emotion Recognition Using Audio and Text](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8639583) | Audio+Text | 2018 | - | - |
|   62.0 |  67.3 | - | CNN+LSTM | [Efficient Emotion Recognition from Speech Using Deep Learning on Spectrograms](https://www.isca-speech.org/archive/Interspeech_2017/pdfs/0200.PDF) | Audio | 2017 | - | - |

### Misc
| UA | WA | F1 | Model | Paper | Modality | Year | Code |  Notes   |
| :-: | :-: | :-: | :-:  | :-: | :-:  | :-:  | :-:  | :-: |
|   80.6 |  82.1 | - | HiGRU | [HiGRU: Hierarchical Gated Recurrent Units for Utterance-Level Emotion Recognition](https://www.aclweb.org/anthology/N19-1037.pdf) | Text | 2019 | [GitHub](https://github.com/wxjiao/HiGRUs) | - |
|   - |  65.25 | 64.18 | DialogueGCN | [DialogueGCN: A Graph Convolutional Neural Network for Emotion Recognition in Conversation](https://arxiv.org/pdf/1908.11540.pdf) | Text | 2019 | - | - |
|   - |  63.40 | 62.75 | DialogueRNN | [DialogueRNN: An Attentive RNN for Emotion Detection in Conversations](https://www.aaai.org/ojs/index.php/AAAI/article/view/4657/4535) | Text | 2019 | [GitHub](https://github.com/SenticNet/conv-emotion/tree/master/DialogueRNN) | - |
|   58.8 |  63.5 | - | RNN | [Automatic Speech Emotion Recognition Using Recurrent Neural Networks with Local Attention](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7952552) | Audio | 2017 | - | - |


## CMU-MOSEI

