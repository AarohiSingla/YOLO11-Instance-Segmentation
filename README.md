## Instance Segmentation Using YOLO11 (Brain Tumor Segmentation)

### Youtube Tuutorial: https://youtu.be/SwG9BSWIpBs

Download Dataset: https://universe.roboflow.com/iotseecs/brain-tumor-yzzav/dataset/1

How to prepare dataset for Instance Segmentation model: https://www.youtube.com/watch?v=a8H_28mdDPo

How to create seperate environment : https://www.youtube.com/watch?v=sKoXJqoqopg

![val_batch0_pred](https://github.com/user-attachments/assets/c110412b-c1c1-4a91-b481-02e96e25ca98)


#### Envronment setup:

	py -3.10 -m venv myvenv
	
	myvenv\Scripts\activate
	
##### Ultralytics recommend to install pytorch first from official website as per your cuda version-  https://pytorch.org/get-started/locally.

	pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu121
    
	pip install Ultralytics
