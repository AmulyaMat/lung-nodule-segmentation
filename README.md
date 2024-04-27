# Lung Nodule Segmentation from Lung CT Scan Images

Dataset: LUNA 16 dataset (using subset0 folder and annotations.csv from https://zenodo.org/records/3723295)
Objective: To do a comparative study of 3 deep learning modules for lung nodule segmentation: U-NET, YOLOv3, Swin-UNET

Common files:

annotations.csv
<img width="790" alt="Screenshot 2024-04-26 at 11 09 32 PM" src="https://github.com/AmulyaMat/lung-nodule-segmentation/assets/143415536/6abb12b0-6b4e-44b7-aff8-c3ccf348f55f">


Code to be preferrably run on Google Colab (so that you don't have to install too many dependencies yourself)

## 1. U-NET
a. Download the 'Model1_UNET' folder
b. For reference: the Processing_UNET.ipynb shows the steps for processing the raw images and converting them into lung and nodule masks for model training (.npy). 
Processed data present in 'Processed_Data' folder
c. Upload all the files onto Google Colab **except** 'Processed_Data' folder, 'Processing_UNET.ipynb', and 'annotations.csv'
d. Read the instructions on the 'BMIAProject_U_NET_Amulya.ipynb' notebook and run it


## 2. YOLOv4
a. Download the 'Model2_YOLO' folder 
b. Upload the 'yolo_10_files' folder and 'BMIAProject_YOLO_Amulya.ipynb' on Google Colab
c. Read the instructions on the 'BMIAProject_YOLO_Amulya.ipynb' notebook and run it


## 3. Swin-UNET [TODO]
a. Download the 'Model3_SwinUNET' folder
b. Upload the ''BMIAProject_YOLO_Amulya.ipynb' on Google Colab
c. Read the instructions on the notebook and run it 
(it is incomplete due to time limitations and code complexity)
