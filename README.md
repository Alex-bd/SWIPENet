# SWIPENet
A novel neural network architecture for dealing with small object detection and noise data in the underwater scenes.
# Dependencies
python >= 3.5
numpy >= 1.18.0
scipy
keras
# DataSets
The underwater robot picking contest datasets is organized by National Natural Science Foundation of China and Dalian
Municipal People’s Government. The Chinese website is http://www.cnurpc.org/index.html and the English website is http:
//en.cnurpc.org/. The contest holds annually from 2017, consisting of online and offline object detection contests. In this
paper, we use URPC2017 and URPC2018 datasets from the online object detection contest. To use the datasets, participants need to communicate with zhuming@dlut.edu.cn and sign a commitment letter for data usage: http://www.cnurpc.org/a/js/2018/0914/102.html
# Usage
Training stage:
1. Train one detection model 
python ssd512_training.py
2. Update the weights using IMA algorithm
python ssd512_updateweight.py
3. Train the second detection model
....

Testing stage:
python ssd512_evaluation.py

# Citation
If you use these models in your research, please cite:



