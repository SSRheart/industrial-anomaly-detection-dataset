# industrial-anomaly-detection-dataset
A curated list of dataset for industrial anomaly detection.

## Table of Contents
+ [2D](#2D)
+ [3D](#3D)
+ [PCB-hub](#PCB-hub)

## 2D

## 3D

## PCB-hub
+ VisA
+ Real-IAD
+ VISION
+ **PKU-Market-PCB**: The dataset has 1386 images with 6 types of common defects, including missing hole, mouse bite, open circuit, short, spur, spurious copper. Half of the images are for the situation where a test PCB is placed correctly, while other half is set for simulating the situation when the test board is randomly orientated in the workbench. It can be download from [[Link]](http://robotics.pkusz.edu.cn/resources/dataset/) or [[Link]](https://www.dropbox.com/s/32kolsaa45z2mpj/PCB_DATASET.zip?dl=0).
+ **PCB Defect-Augmented**: Considering the defect images of PKU-Market-PCB are high-resolution. With the respect of such small dataset, data augmentation techniques are adopted before data training. The images are then cropped into 600 × 600 sub-images, forming our training set and testing set with 9920 and 2508 images, respectively. [[BaiduYUN]](https://pan.baidu.com/s/1eAxDF4txpgMInxbmNDX0Zw) Code: a6rh. [[Dropbox]](https://www.dropbox.com/s/h0f39nyotddibsb/VOC_PCB.zip?dl=0)
+ **FICS-PCB**: It is collected at the SeCurity and AssuraNce (SCAN) Lab at the University of Florida, and it is a part of an on-going multi-modality PCB data collection effort. The dataset currently consists of 9,912 images acquired from 31 PCBs that were purchased online or disassembled from various devices, including hard drive controllers, audio amplifiers, monitors, etc. Four board colors, green, red, blue, and black, are currently represented. [[Link](https://www.trust-hub.org/#/data/pcb-images)
+ **Deep-PCB**: The dataset contains 1,500 image pairs, each of which consists of a defect-free template image and an aligned tested image with annotations including positions of 6 most common types of PCB defects: open, short, mousebite, spur, pin hole and spurious copper.[[Link]](https://github.com/tangsanli5201/DeepPCB/tree/master/PCBData)
+ **PCB-DSLR**: The PCB DSLR dataset is meant to facilitate research on computer-vision-based Printed Circuit Board (PCB) analysis, with a focus on recycling-related applications. The dataset contains 748 images of PCBs from a recycling facility, captured under representative conditions using a professional DSLR camera. All images come with accurate PCB segmentation information as well as bounding box information for all Integrated Circuit (IC) chips (9313 samples). [[Link]](https://zenodo.org/records/3886553)
+ **PCB-METAL**: Not released.
+ **NV-PCB Internal Dataset**: Not released
+ **Micro-PCB**: This dataset consists of a total of 8,125 images of 13 micro-PCBs in high resolution. The average size of all images is 1949×2126 (width×height). The micro-PCBs were captured in 25 different positions relative to the camera under ideal lighting conditions. In each position, each micro-PCB was captured in 5 different rotations. This creates 125 unique orientations of each micro-PCB relative to the camera. No micro-PCB that is used in training is the same that is used in testing In total, each micro-PCB in the dataset has 500 training images and 125 test images, creating an overall train/test split of 6,500/1,625. [[Link]](https://www.kaggle.com/datasets/frettapper/micropcb-images)
+ **PCB_Compement_Defection**:
The dataset collected and labeled 48 PCB images from human experts to construct a dataset for training and testing. It is split into 40 for training and 8 for testing. Some of the PCB images are from the Internet while others are taken from a DSLR camera or an industrial camera. Consequently, the lighting condition, resolution, quality. etc. vary substantially across images.  [[Link]](https://sites.google.com/view/chiawen-kuo/home/pcb-component-detection)
+ **PCB-Vision**:The dataset includes:
RGB images of 53 PCBs scanned with a high-resolution RGB camera (Teledyne Dalsa C4020).
53 hyperspectral data cubes of those PCBs scanned with Specim FX10 in the VNIR range.
Two segmentation ground truth files: 'General' and 'Monoseg' for 4 classes of interest - 'others,' 'IC,' 'Capacitor,' and 'Connectors.'.  [[Link]](https://rodare.hzdr.de/record/2704 or https://zenodo.org/records/10617721)
+ **MPI-PCB Dataset**:
The Multi-Perspective and Illumination PCB (MPI-PCB) dataset contains 1742 images with dimensions of 4096 × 2816-pixel showing an unmodified PCB from a gas pump. The images were captured using a Canon EOS 1100D camera with 18–55 mm lenses. The set also contains 55 images showing the board with modifications manually added by the authors, which are meant to be representative of situations encountered in actual frauds. These samples also contains labeled semantic segmentation masks that represents the localization of the frauds, being able to execute the comparision between different techniques. [[Link]](https://zenodo.org/records/8213098#:~:text=The%20Multi%2DPerspective%20and%20Illumination,with%2018%E2%80%9355%20mm%20lenses)
+ **PCB-AoI Public Dataset**:
This dataset is part of the open-source distributed synergy AI benchmarking project KubeEdge-Ianvs. It is released by KubeEdge SIG AI members from China Telecom and Raisecom Technology.More than 230 boards is collected and enhanced to 1200+ images.
https://www.kaggle.com/datasets/kubeedgeianvs/pcb-aoi
MIXED PCB DEFECT DATASET
This dataset contains images focusing on printed circuit boards (PCBs) and their defects. To maintain uniformity, the images are resized to a standard 640 x 640 pixels. Various augmentation techniques were used to diversify the dataset, ensuring better algorithm performance during training and evaluation. The dataset features annotations that precisely label the induced defects, such as missing holes, mouse bites, open circuits, shorts, spurs, and spurious copper issues. [[Link]](https://data.mendeley.com/datasets/fj4krvmrr5/2)
+ **U-PCBD**:
U-PCBD consists of two versions: version 1 and version 2. Version 1: This version of the dataset is obtained by scanning surfaces of 20 PCB samples, which includes 200 original images of 640 * 640 pixels. It is then expanded to 4320 images by data augmentation including flipping, rotating, brightening, blurring and noising. There are 14346 defect annotations in the final dataset. The detailed information is presented in Table 1. The training set includes 3456 images, and test set includes 864 images.
Verion 2: This version of the dataset is obtained by scanning the surfaces and internal layers of 50 multi-layer PCB samples, which includes 425 original surface images of 640 * 640 pixels and 84 original internal layer images of 640 * 640 pixels. It is then expanded to 15300 surface images and 3024 internal images by data augmentation including flipping, rotating, brightening, blurring and noising. There are 47880 defect annotations in the final dataset. The detailed information is presented in Table 2. The training set includes 14660 images, and test set includes 3664 images. [[Link]](https://iiplab.net/u-pcbd/)
+ **RF100**: The dataset cover PCB objects. The training set, validation set, and test set are 548, 80, and 44 images respectively. [[Link]](https://universe.roboflow.com/roboflow-100/printed-circuit-board)


