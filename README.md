
# Facial Emotion Recoginition

Traditional facial expression recognition systems
that used machine learning required a lot of preprocessing,
yet they achieved sub-optimal accuracy. As neural networks
came into action, more and more tasks were completed with
simpler models, and they removed many redundant preprocessing
steps. As convolutional networks became popular, the networks
got deeper and contained millions of parameters leading to
superhuman accuracy. Human Facial Expression Recognition is
one such task where a lot of research is going on.


The dataset is called FER2013 and is available [here](https://www.kaggle.com/datasets/msambare/fer2013).
The dataset contains two folders named train and test.
The train folder contains 28709 images that can be used for
training. The test folder contains 7178 images that can be used
to evaluate the trained models. Both the folders contain seven
sub folders each and they represent unique emotions. Thus the
dataset has seven classes each representing an emotion. Below image shows different classes present in the dataset.

![Emotions](https://github.com/pranjal-dave/Emotion-Recognition/blob/main/emotion.PNG)

As there is a high imbalance in the representation of
different emotions in the FER2013 dataset, the state of the
art models also fail to achieve a very high accuracy. Other preprocessing steps included me using the Data Augmentation strategy with
width shift range = 0.1, height shift range = 0.1, horizontal
flipping and re-scaling to [0,255] to [0,1].
The train set was also split into train-validation set for
training in 80-20 ratio.

