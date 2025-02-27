# Silent EEG classification using cross-fusion adaptive graph convolution network for multilingual neurolinguistic signal decoding


You should build a graph for each feature matrix. Each feature matrix has its unique graph.
The inputs of cross-fusion adaptive graph convolution network are each feature and its graph.

There are the original dataset links at:https://drive.google.com/drive/folders/1z42JhviUJRevvHJ07tD1xbFLakTj04rN?usp=sharing (Silent reading EEG signals of English words) 
https://drive.google.com/drive/folders/1k3IiZneBqgxEQWguCzhE-2nBxvupDmaj?usp=sharing (Silent reading EEG signals of Chinese words)

For each experimental group, three files are generated: data.bdf, evt.bdf, and recordInformation.json. 
Each data.bdf file contains all the EEG signals collected from the beginning to the end of each trial. 
Each evt.bdf file contains EEG data points and their corresponding markers.
The recordInformation.json file contains information such as the date of the experiment and other metadata recorded by the experiment supervisor.
Given that the data.bdf file comprises a set of experiments involving the 'listening', 'silent reading', and 'speaking' conditions. The data is first cropped based on the markers and corresponding data points in the evt.bdf file. 
Cutting the data according to the marks and the meaning of marks, please reference the experiment procedure.

![image](https://github.com/cfli20/cross-fusion-adaptive-graph-convolution-network/assets/32564661/245c833f-7720-4db7-9b8d-686d6da43ed7)

The readout is not very complete when using Python; there may be encoding or formatting problems.
We recommend that you use MATLAB. You need to install the plugin and select both data.bdf and evt.bdf when reading. Download the plugin at The https://drive.google.com/drive/folders/1vSg8RZJ0iVUdv5QvBLvrSFiQGyCg_AtE 
Release note has detailed installation instructions
Read the labels and then crop the individual tasks to a uniform size.


Thank for citing our paper:

@article{li2024silent,
  title={Silent EEG classification using cross-fusion adaptive graph convolution network for multilingual neurolinguistic signal decoding},
  author={Li, Chengfang and Wang, Hanqi and Liu, Yang and Zhu, Xiaoguang and Song, Liang},
  journal={Biomedical Signal Processing and Control},
  volume={87},
  pages={105524},
  year={2024},
  publisher={Elsevier}
}

 
