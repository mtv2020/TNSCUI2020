# TNSCUI2020
Thyroid Nodule Segmentation and Classification in Ultrasound Images
![alt text](https://github.com/mtv2020/TNSCUI2020/blob/master/Untitled.png?raw=true)
Dataset
    In the challenge, the participants will be provided the US nodular thyroid dataset supplied by Shanghai Ruijin Hospital. This data comes from the Chinese Medical Ultrasound Artificial Intelligence Alliance (CMUAA) initiated by doctor JianQiao Zhou. The dataset includes training set images and testing set images in grayscale and .png extension from different equipments and sizes. All personal labels of scan images were removed in order to protect patients' privacy.
    The training set: 3644 US nodular thyroid images of 3644 patients. The annotation of nodules is labeled by experienced doctors. The annotation images for segmentation task are binary images in which pixels are either 1 for the foreground or 0 for the background. The annotation images named as “xxx.png”. Where “xxx” presents patient ID (from 001 to 3644). The annotation of the classification task is in CSV file with a header of PID (denotes for patient ID) and CATE (0 refer to Benign, and 1 refers to malignant).
