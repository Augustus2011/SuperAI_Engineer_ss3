round 1
data
-lumbar spine(l1-l5) included sarcral(s1)
-800 image train set of AP,LA view ,200 image test set mixed AP,LA view
-800 location for each joint.csv

do.. detection for the joint position

evaluation metric==MSE
approch
1.time series on .csv ,idea joint positions are like wave and its depend on previos joint(squence)  (bad).
2.yolo detection boxes(fair).
3.Segment then do detection(best).

![image](https://github.com/Augustus2011/SuperAI_Engineer_ss3/assets/107476202/2a4ef81c-8b3c-48c6-b639-d458c4307de0)

round 2

data
-la,ap view same as the first round but more 2100 images
do..1.gender classification 2.vertebral position as round 1 3.classify abnormals from their posotions(2.)

evaluation metrics 1.acc exact match 2.mse 3.f1-micro
