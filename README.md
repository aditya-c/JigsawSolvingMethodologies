# JigsawSolvingMethodologies

Login to ieng6:

`ssh ee285fay@ieng6.ucsd.edu`

Start Pytorch pod:

`K8S_NUM_CPU=4 K8S_TIMEOUT_SECONDS=43200 launch-py3torch-gpu.sh -m 32 -v gtx1080ti -g 1`

Clone the repo:

`git clone https://github.com/aditya-c/JigsawSolvingMethodologies.git`

Open the jupyter link and run the notebook located at JigsawSolvingMethodologies/project/jigsawvggstl.ipynb

Code for unsupervised learning can be found [here](https://github.com/aditya-c/JigsawSolvingMethodologies/tree/master/Semisupervised_Image_Classifier)

This code was used to compare the performance of our model to that of an unsupervised learning model
