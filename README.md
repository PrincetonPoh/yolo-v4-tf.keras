# Introduction
This is a simple project for a course on Unstructured Data. I followed [this](https://neptune.ai/blog/object-detection-with-yolo-hands-on-tutorial) tutorial which in turn uses a YoloV4 implementation [here](https://github.com/taipingeric/yolo-v4-tf.keras).

# Dataset
I followed the tutorial fully but trained it on a custom annotated dataset of potholes. The dataset can be found [here](https://www.kaggle.com/datasets/chitholian/annotated-potholes-dataset/data).

# Weights
I've trained a model using the train.ipynb and the weights is stored in a hdf5 file that can be downloaded from [here](https://drive.google.com/file/d/1MFrprdJLhMMixsnvhOQa0W2ftxzr9jqi/view?usp=sharing)

# Further learnings
I can attempt these simple things:

- [ ] Mosaic augmentation
- [ ] DropBlock
- [ ] Self-adversarial training (SAT)
- [ ] Label smoothing
- [X] Cosine annealing scheduler
- [X] mAP
- [X] Mish
- [X] IoU, GIoU, CIoU loss 
- [X] multi-GPU training
