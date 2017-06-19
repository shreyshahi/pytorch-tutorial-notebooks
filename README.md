# pytorch-tutorial-notebooks
Practice notebooks I used to follow along various pytorch tutorials

The notebooks mostly cover material from:
- http://pytorch.org/tutorials/
- https://github.com/pytorch/examples

To setup the environment for running these notebooks follow these steps:
- Install python3.6 if not already on system
- create a virtualenv using `mkvirtualenv pytorch --python=python3.6`
- install the dependencies using `pip install -r requirements.txt`

Note that my requirements.txt is for a linux system with Cuda8.0 installed, follow the instructions at http://pytorch.org/ if you are not using linux or cuda8.0. Also note that pytorch is currently in an early release beta and is changing very quickly, the code in these notebooks will likely break with future API changes. 
