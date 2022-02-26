# Amazon rainforest analysis with Efficientnet

This notebook is based on kaggle competition "Planet: Understanding the Amazon from Space"  
link : https://www.kaggle.com/c/planet-understanding-the-amazon-from-space/overview

To run this code, you need following dependencies installed:
- tensorflow
- tensorflow_addons
- keras
- numpy
- pandas
- cv2
- tqdm
- matplotlib

Also, download dataset from the link above and unzip the files.
We will use train_v2.csv and image files from train-jpg folder, so provide each of these files to methods pd.read_csv() and cv2.imread() respectively.

Train results are as follows:
Early stoppage occurs at epoch 22 with f-beta score of 0.9508
![](./img/execution.png)

F-beta Score graph:
![](./img/history.png)

