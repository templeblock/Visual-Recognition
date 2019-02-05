# CS783-Visual-Recognition-Assignment-1

This repository contains the assignments for the course CS783: Visual Recognition, as done by Amrit Singhal(150092) and Aarsh Prakash Agarwal(150004).

## Resnet Training and Testing
For this code to run you should have following directories outisde the directory your code is in.

`working` This is where your code will be stored after the training is done. Should be empty at first.

`test_results` This where the ranking of the images will be stored for the testdata

`test` Should contain all the test files inside single folder inside this folder.

`train` Contains folder of the classes of the objects one wants to train on

`valid` Contains folder of the classes of the objects for validation with same folder name of the classes as present in train folder. Note that in the original dataset you only have train images. You can split 36 random images from each folder create validation set.

`dataset_train` The folder contains folder `train` with the original dataset inside it.

`resnet50` The folder contains pretained weight vectors of the RESNET model. Can be downloaded from kaggle easily.

Use `python resnet.py` to train and save model on you disk. Weingts will be stored in the working folder.

Use `python resnet_categorisation.py` for testing your results.





