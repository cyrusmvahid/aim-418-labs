# Environmnet set up
To install Conda please refer to [this link](https://docs.conda.io/projects/conda/en/latest/user-guide/install/index.html)
```
 conda create -n HUB python=3.6 anaconda
 source activate HUB
 pip install numpy mxnet jupyter seaborn matplotlib pandas scipy gluoncv gluonnlp scikit-learn
 #test your environment
 which python
 # shoud result in <your conda path>//envs/HUB/bin/python
 python --version
 #Python 3.6.8 :: Anaconda, Inc.
 #To leave the environment
 conda deactivate
 ```
 
 To get this repository, please run:
 git clone https://github.com/cyrusmvahid/aim-418-labs.git
 
# Study Materials:
- gluon tutorials: http://mxnet.incubator.apache.org/versions/master/tutorials/index.html 
- reference book: http://d2l.ai/
- related repos:
  - https://github.com/cyrusmvahid/GluonBootcamp
  - https://github.com/cyrusmvahid/KDD18-Gluon
  - https://github.com/cyrusmvahid/MXNetWorkshopHongKong
  - https://github.com/cyrusmvahid/HKUSTLectures
  - https://github.com/cyrusmvahid/HUBCourse
  
 # Running on Collab
 - Lab 2: https://colab.research.google.com/github/cyrusmvahid/aim-418-labs/blob/master/collab-cu100/lab02-ndarray.ipynb
 - Lab 3: https://colab.research.google.com/github/cyrusmvahid/aim-418-labs/blob/master/collab-cu100/lab03-autograd.ipynb
 - Lab 4: https://colab.research.google.com/github/cyrusmvahid/aim-418-labs/blob/master/collab-cu100/lab04-nn.ipynb
 - Lab 5: https://colab.research.google.com/github/cyrusmvahid/aim-418-labs/blob/master/collab-cu100/lab05-training.ipynb
 - LSTM: 
 
 