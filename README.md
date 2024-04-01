This is human feature extraction project.
The purpose of this project to extract human foregorund and we can further replace with different backgrounds.

Training
Collecting data from coco we only human images and masks.
We use that data and fine tune with u net and use different backbone architecture Efficientnet_b7, resnet18
Then make weight average prediction for better accuracy

Infer
Use the finetuned models and make prediction on real time web cam

Here is the training and single image infer link
https://www.kaggle.com/code/myominhtet/notebook167504d7e3/notebook
