# Attention Based Object Co-segmentation

  - Object Cosegmentation with Deep learning and Attention Module
  - Capable of segment unseen obejct
  - Cosegment multiple inputs with linear time.
 
 Inspired by ACCV 2018
 https://arxiv.org/abs/1810.06859
 

# Pretrained model
You can download from here! 

smb://docs.oxagile.com/upload/OxagileDL/Media-Entertainment/AI/models/RM-76/epoch1iter5000.pkl

Put it into the models folder.

# Install

Here is the list of libraries you need to install to execute the code:
- python = 3.6
- [pytorch](http://pytorch.org/) = 0.4
- Pillow
- Numpy
- Glob

Use 'pip install -r requirements.txt' for installing Pillow, Numpy and Glob. 

## Co-segment two images
For example:
```
python two_image_performance.py --image1 "two_image_demo/h1.jpg" --image2 "two_image_demo/h2.jpg" --model "models/epoch1iter5000.pkl"
```

## Co-segment multiple images
For example:
```
python group_image_performance.py --image_path "group_image_demo/" --model "models/epoch1iter5000.pkl"
```
