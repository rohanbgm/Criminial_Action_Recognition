# Criminial_Action_Recognition
Recognising a human action is one of the complex
tasks a computer can perform. More often building a model that
differentiates between two distinct actions of a human being is
quite easy to implement but to build a model that differentiates
multiple similar, as well as distinct actions of a human being, is
quite challenging. So to overcome this problem we have built an
action recognition model which recognises human action using
the human skeletal key-point detection technique. To perform
real-time multi-person skeletal key-point detection we have used
the OpenPose library which detects 135 key-points in total. To
perform the action recognition we have implemented AdaBoost
and MLP algorithm. We have performed a two-class and multiclass classification using imbalanced data and balanced data in
which MLP with balanced data achieved the highest f1-score in
the two-class classification and in the multi-class classification
scenario. In this experiment, we examine the behaviour of a
model when a complicated real-time situation arises and how it
impacts the performance of the model as seen between two-class
and multi-class classification. The UCF-crime dataset was used
to build this model which was made up of live video footage
obtained from the surveillance cameras
