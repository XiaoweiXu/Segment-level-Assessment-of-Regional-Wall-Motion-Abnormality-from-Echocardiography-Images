# Segment-level-Assessment-of-Regional-Wall-Motion-Abnormality-from-Echocardiography-Images

Regional wall motion assessment is critical in the diagnosis of coronary artery diseases, and is usually performed using echocardiography images in clinical practice. 
However, manual assessment of regional wall motion is time-consuming and requires expertise. 

Thus, we published SegRWMA, a segmentation dataset for automatic segment-level assessment of regional wall motion abnormality

Our dataset consists of 198 patients where for each patient three views (A4C, A3C, and A2C) in three modes (2D mode, MCE mode, and LVO mode). Thus, there are totally 1,782 echocardiography videos, with the varying frame size of 640*480*(71-510). A total of 9881 frames of echocardiography images in three modalities are collected, in which, there are 3,091, 3,391 and 3,399 frames in the 2D mode, LVO mode, and MCE mode, respectively. For each video, six frames (two end-systolic frames, two end-diastolic frames, and two frames between between the end-diastolic and end-systolic frames) are selected for annotation, and the regional wall contour of the left ventricular is labeled as shown in Fig. \ref{fig_segment}. A total of 3,564 segments are labeled in all the 198 patients, among which 45 segments are abnormal. Note that such low incidence rate is a reflection of the real-life statistics of clinical practice at our center. All labels were annotated by four experienced sonographers, and each taking about 5 minutes to finish.

**HIGHLIGHT** 20231101: We have deployed the dataset on Kaggle! https://www.kaggle.com/xiaoweixumedicalai/datasets

Please send emails to xiao.wei.xu@foxmail.com for any questions.
