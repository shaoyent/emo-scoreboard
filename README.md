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
| 77.6 | 76.5 | - | Multi Hop Attention | [Speech Emotion Recognition Using Multi-hop Attention Mechanism](https://ieeexplore.ieee.org/abstract/document/8683483) | Audio+Text | 2019 | - | - |
| 65.9 | 64.97 | - | E-vector + MCNN + LSTM | [Deep neural networks for emotion recognition combining audio and transcripts](https://arxiv.org/pdf/1911.00432.pdf) | Audio+Text | 2019 | - | - |
| 65.7 | - | - | ProgNet | [Progressive Neural Networks for Transfer Learning in Emotion Recognition](https://arxiv.org/pdf/1706.03256.pdf) | Audio | 2017 | - | - |
| 64.74 | - | - | 3D ACRNN | [3-D Convolutional Recurrent Neural Networks With Attention Model for Speech Emotion Recognition](https://ieeexplore.ieee.org/document/8421023) | Audio | 2018 | [GitHub](https://github.com/xuanjihe/speech-emotion-recognition) | - |
| 61.7 | 64.5 | - | CNN+LSTM | [CNN+LSTM Architecture for Speech Emotion Recognition with Data Augmentation](https://arxiv.org/pdf/1802.05630v2.pdf) | Audio | 2019 | - | - |

### 5-fold cross validation
| UA | WA | F1 | Model | Paper | Modality | Year | Code |  Notes   |
| :-: | :-: | :-: | :-:  | :-: | :-:  | :-:  | :-:  | :-: |
|  - |  71.8 | - | RNN | [Multimodal Speech Emotion Recognition Using Audio and Text](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8639583) | Audio+Text | 2018 | [GitHub](https://github.com/david-yoon/multimodal-speech-emotion) | - |
|   62.0 |  67.3 | - | CNN+LSTM | [Efficient Emotion Recognition from Speech Using Deep Learning on Spectrograms](https://www.isca-speech.org/archive/Interspeech_2017/pdfs/0200.PDF) | Audio | 2017 | - | - |

### Misc
| UA | WA | F1 | Model | Paper | Modality | Year | Code |  Notes   |
| :-: | :-: | :-: | :-:  | :-: | :-:  | :-:  | :-:  | :-: |
|   80.6 |  82.1 | - | HiGRU | [HiGRU: Hierarchical Gated Recurrent Units for Utterance-Level Emotion Recognition](https://www.aclweb.org/anthology/N19-1037.pdf) | Text | 2019 | [GitHub](https://github.com/wxjiao/HiGRUs) | - |
|   - |  65.25 | 64.18 | DialogueGCN | [DialogueGCN: A Graph Convolutional Neural Network for Emotion Recognition in Conversation](https://arxiv.org/pdf/1908.11540.pdf) | Text | 2019 | [GitHub](https://github.com/SenticNet/conv-emotion) | - |
|   - |  63.40 | 62.75 | DialogueRNN | [DialogueRNN: An Attentive RNN for Emotion Detection in Conversations](https://www.aaai.org/ojs/index.php/AAAI/article/view/4657/4535) | Text | 2019 | [GitHub](https://github.com/SenticNet/conv-emotion/tree/master/DialogueRNN) | - |
|   58.8 |  63.5 | - | RNN | [Automatic Speech Emotion Recognition Using Recurrent Neural Networks with Local Attention](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7952552) | Audio | 2017 | - | - |


## CMU-MOSEI

## MSP-IMPROV
### 10-fold cross validation
| UAR | Model | Paper | Modality | Year | Code |  Notes   |
| :-: | :-: | :-: | :-:  | :-: | :-:  | :-:  | :-:  | :-: |
| 52.6  | - |[USING REGIONAL SALIENCY FOR SPEECH EMOTION RECOGNITION](https://ieeexplore.ieee.org/abstract/document/7952655) | - | 2017 | - | -|
| 60.5  | - |[Progressive Neural Networks for Transfer Learning in Emotion Recognition](https://arxiv.org/pdf/1706.03256.pdf) | - | 2017 | - | -|
| 55.98 | - |[EXPLOITING ACOUSTIC AND LEXICAL PROPERTIES OF PHONEMES TO RECOGNIZE VALENCE FROM SPEECH ](https://ieeexplore.ieee.org/abstract/document/8683190) | - | 2019 | - | -|
| 52.43 | - |[Direct Modelling of Speech Emotion from Raw Speech](https://arxiv.org/pdf/1904.03833.pdf) | - | 2020 | - | -|


