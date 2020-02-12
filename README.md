# ECG-Arrhythmia-Classification
In this project I have classified ECG into normal and non normal types of arrhythmia using deep two-dimensional CNN with grayscale ECG images. By transforming one-dimensional ECG signals into two-dimensional ECG images, noise filtering and feature extraction are no longer required. This is important since some of ECG beats are ignored in noise filtering and feature extraction. In addition, training data can be enlarged by augmenting the ECG images which results in higher classification accuracy. Data augmentation is hard to be applied in 1-d signals since the distortion of 1-d ECG signal could downgrade the performance of the classifier. However, augmenting two-dimensional ECG images with different cropping methods helps the CNN model to train with different viewpoints of the single ECG images. Using ECG image as an input data of the ECG arrhythmia classification also benefits in the sense of robustness.

Inside the dspimage folder , L folder contains the images of Non normal heartbeat and the N folder contains the images of Normal heartbeat

I have reached a decent accuracy of 80% on my CNN model

Youtube Video:

https://youtu.be/O1f5-yn-NZ4
