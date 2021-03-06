This dataset (npVCC2016) is subset of VCC2016 dataset.  
Original VCC2016 dataset contains parallel utterances, but this subset is intended to be used for non-parallel tasks.  
Data division is based on ["PARALLEL-DATA-FREE VOICE CONVERSION USING CYCLE-CONSISTENT ADVERSARIAL NETWORKS"](https://arxiv.org/abs/1711.11293).  

# Contents and its characters
npVCC2016 contains total 540 utterances from 4 speakers.  
These utterances is subset of [VCC2016 dataset](https://doi.org/10.7488/ds/1575).  
Data is structured and characterized are as below.  

* trains
  + SF1: female#1, 81 utterances (100001 - 100081)
  + SM1: female#1, 81 utterances (100001 - 100081)
  + TF2: female#2, 81 utterances (100082 - 100162)
  + TM3: male#3,   81 utterances (100082 - 100162)
* evals
  + SF1: female#1, 54 utterances (200001 - 200054)
  + SM1: female#1, 54 utterances (200001 - 200054)
  + TF2: female#2, 54 utterances (200001 - 200054)
  + TM3: male#3,   54 utterances (200001 - 200054)

Sxx is intended as **S**ource speaker, and Tyy is intended as **T**arget speaker.  
It means that Sxx and Tyy (e.g. SF1 and TF2, SF1 and TM3) are non-parallel.  
In other words, Sxx and Syy (e.g. SF1 and SM1) is parallel.  
evals is all same words.  

All audio is monaural 16 kHz[^5], 16-bit[^6], RIFF/WAVE format[^4]  
[^4]: > The waveforms in the directory are in RIFF/WAVE format.  
[^5]: > The sampling rate is 16 kHz  
[^6]: > stored in 16-bit format.  

# Licence
VCC2016 is Creative Commons License: Attribution 4.0 International.  
This subset also follow this.  
