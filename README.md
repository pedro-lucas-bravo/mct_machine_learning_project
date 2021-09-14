# Estimation of Direction of Arrival (DOA) for First Order Ambisonic Audio Files using Artificial Neural Networks

**Pedro Pablo Lucas Bravo**

**University of Oslo (UiO), Norwegian University of Science and Technology (NTNU)**

**Music, Comunication and Technology Master Programme**

**pedropl@uio.no**

*I am registered on MCT4047 UiO's Studentweb*

**In the notebook [file.ipybn](file.ipynb) you will find this content. You can navigate to other notebooks from there.**

The aim of this project is to develop a solution to estimate the *Direction of Arrival(DOA)* from a sound event enconded as a *First Order Ambisonic* audio file (4-channel). The source code is organized in several Jupyter notebooks that are linked to the instructions given below.

For executing the project follow the next steps (After downloading the data, you can executed any of them if the focus is in one of these stages). Every notebook has an aproximate execution time provided below:

1. Download the data from [x](), uncompress the folder at the level of this file.ipynb. You should be able to have a new folder called **data** that contains another folder called **dcase_data**.

2. Execute the notebook [feature_extraction.ipybn](feature_extraction.ipynb). Here you can generate the features for traning and testing and save them to files if needed. (Exec. time 30 min)

3. Execute the notebook [training.ipybn](training.ipynb). In this notebook the features for training will be loaded from one of the files generated in the previous step. Here the models will be saved if needed. (Exec. time 10 min)

4. Execute the notebook [inference.ipybn](inference.ipynb). The data from the features for testing will be loaded to show performance metrics related with instances that the ML algorithm do not consider in the training process. (Exec. time 15 sec)

Experiments regarding feature extraction and training can be found in the folder [experiments](./experiments). They will NOT run since they are not in the root folder, but they show part of the effort to find the right features and network architecture.