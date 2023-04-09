# Demo visualization code for our PoseFormer paper

- Create a conda environment: ```conda create -n mhformer python=3.7```
- Install pytorch based on your machine. For example:
- ```pip3 install torch==1.7.1+cu110 torchvision==0.8.2+cu110 -f https://download.pytorch.org/whl/torch_stable.html```
- Next, Install required packages:
- ```pip3 install -r requirements.txt```

## Download pretrained model for video demo

The pretrained model can be found in [here](https://drive.google.com/file/d/1nCd8YxaLGztZAnAiL_zFDg036J9QRLDI/view?usp=sharing), please download it and put it in the './checkpoint/poseformer_9' directory. 

## Demo
First, you need to download YOLOv3 and HRNet pretrained models [here](https://drive.google.com/drive/folders/1_ENAMOsPM7FXmdYRbkwbFHgzQq_B_NQA?usp=sharing) and put it in the './demo/lib/checkpoint' directory. 
Then, you need to put your in-the-wild videos in the './demo/video' directory. 

Run the command below:
```bash
python demo/vis_poseformer.py --video kunkun.mp4
```

## Licence

This project is licensed under the terms of the MIT license.
