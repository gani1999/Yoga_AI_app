## Yoga_AI_app
Smart AI Yoga assistant, which helps to predict our pose and to correct our yoga pose through the feedback generated in live.

### Introduction:
To live long and live healthy, it’s really important to do some physical activities in our daily routine. But we always run behind money and end our day in stress. To overcome this and to have a balanced life cycle one must practice yoga or any physical activity that relieves stress. Nowadays, yoga has gained worldwide attention due to increased stress levels in the modern lifestyle. +e word yoga means deep association and union of mind with the body. It is used to keep both mind and body in equilibration in all flip-flops of life by means of asana, meditation, and several other techniques.

There are many ways to practice yoga, like Yoga centers, Temples, etc. But due to the busy life people tend to self-taught themselves. But in self-learning, one may not find an incorrect pose. Incorrect posture while performing yoga can lead to serious harm to muscles and ligaments of the body. Thus, to prevent this we present an intuitive approach based on deep learning techniques to correct the practitioner’s pose while performing various yoga asanas. The proposed system is aimed at providing concise feedback to the practitioner so they can able to perform yoga poses correctly and assist them in identifying the incorrect poses and suggest proper feedback for improvement in order to prevent injuries as well as increase their knowledge of a particular yoga pose.

### ML Formulation:
This can be formulated as a machine learning classification problem, where we first need to estimate the pose (Asanas) that practitioner wants to perform. Once the pose prediction was done, we can perform some geometrical analysis on the pose and generate precise feedback to the practitioner.

### Business Constraints:
1. Strict latency requirement:
Our model must be able to estimate the pose fast within seconds.

2. Cost of misclassification:
If our model predicts one pose instead of other then our whole process generates different feedback and it becomes a mess. So, there should be no misclassification.

### Data source:
https://www.kaggle.com/datasets/niharika41298/yoga-poses-dataset

it contains 5 yoga poses

1. Down dog
2. Goddess
3. Plank
4. Tree
5. Warrior

### Performance metrics:
1. Confusion matrix
2. Area under curve (AUC)
3. F1 score

### References:
1. https://link.springer.com/article/10.1007/s11227-021-04076-w
2. https://arxiv.org/abs/2004.10362
3. Yog-Guru: Real-Time Yoga Pose Correction System Using Deep Learning Methods | IEEE Conference Publication | IEEE Xplore
4. https://www.itm-conferences.org/articles/itmconf/pdf/2021/05/itmconf_icacc2021_03031.pdf
