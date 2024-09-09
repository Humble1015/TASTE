# TASTE
TASTE : A Two-Stage Offloading Strategy for Efficient Human Action Recognition in Edge Computing

This repository contains the PyTorch imploymentation for the TASTE. If you have any questions on this repository or related paper, feel free to create an issue or send me an email.
Migrate code to the following environment: 
Python 3.10 
Torch 2.0.1 
Cuda 10.0 
Numpy 1.24.3 
Torch-sctter 2.1.1 
Torch-geometric 2.3.1 
Scikit-learn 1.2.2

Training TASTE: Assume that you are under the RL direction of this project, and with NTU-RGB+D 60 dataset in correct posotion, the ralated configs are in the root of this project. And the related configs are in the config1.json. 
python dqn.py.
If you want to train other compare experiments (on the same direction): 
python one.py 
python task-sceldule.py 
python ran.py

Training PPO: Assume that you are under the RLppo direction of this project. And the related config are in the config1.py. 
python pporun.py

We will clean and release the code soon. If you have any question, please feel free to contact me : 19590787724@qq.com
