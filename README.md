# LSTM-Transformer-SER
This is an attempt as an unofficial code for the paper titled "Hybrid LSTM-Transformer Model for Emotion Recognition From Speech Audio Files" 
Coded by: Anisa Bente Newaz
Main Paper Authors: F. Aandayani, L. Theng, M. Tsun, AND C. Chua

## Abstract

Emotion is a vital component in daily human communication and it helps people understand each other. Emotion recognition plays a crucial role in developing human-computer interaction and
computer-based speech emotion recognition. In a nutshell, Speech Emotion Recognition (SER) recognizes emotion signals transmitted through human speech or daily conversation where the emotions in a speech strongly depend on temporal information. Despite the fact that much existing research showed that a hybrid system performs better than traditional single classifiers used in SER, there are some limitations in each of them. As a result, this paper discussed a proposed hybrid Long Short-Term Memory (LSTM) Network and Transformer Encoder to learn the long-term dependencies in speech signals and classify emotions. Speech features are extracted with Mel Frequency Cepstral Coefficient (MFCC) and fed into the proposed hybrid LSTM-Transformer classifier. A range of performance evaluations was conducted on the proposed LSTM-Transformer model. Though the paper claims to have 75.62% accuracy for RAVDESS dataset, this code finds 54.5% accuracy. 

## Requirement
tensorflow <br>
librosa <br>
numpy <br>
pandas <br>
scikit-learn <br>

## How to run the code

Step 1: Download RAVDESS dataset and copy the datapath. There are 24 actors, every actors folder has 60 wav format files. You need to show the global folder path which contains all actors. <br>
<br>
Step 2: python main.py --datapath [datapath]

## References:

```bibtex
@article{andayani2022hybrid,
  title={Hybrid LSTM-transformer model for emotion recognition from speech audio files},
  author={Andayani, Felicia and Theng, Lau Bee and Tsun, Mark Teekit and Chua, Caslon},
  journal={IEEE Access},
  volume={10},
  pages={36018--36027},
  year={2022},
  publisher={IEEE}
}

