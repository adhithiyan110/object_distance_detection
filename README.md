
## Jetson Nano - Ubuntu 20.04 image with OpenCV, TensorFlow and Pytorch

#### Version
- Ubuntu 20.04.

- OpenCV (4.8.0)

- PyTorch (1.13.0)

- TorchVision (0.14.0)

- TensorRT (8.0.1.6)


### Installation
- Get a 32 GB (minimal) SD card to hold the image.
- Download the image `JetsonNanoUb20_3b.img.xz` (**8.7 GByte!**) from link
link_1 - [Sync](https://ln5.sync.com/dl/403a73c60/bqppm39m-mh4qippt-u5mhyyfi-nnma8c4t). 

link_2 - [Google Drive](https://drive.google.com/file/d/1L2H_sQC_kSILrcJteWg7htKxJirtDsZ9/view?usp=sharing)

- Flash the image on the SD card with the [Pi Imager](https://www.raspberrypi.org/software/)

- Insert the SD card in your Jetson Nano

- Password: ***jetson***

### General Installation
```
pip install opencv-python
```
```
pip install pyrealsense2
```
```
pip install ultralytics
```
### Running Distance detection
```
git clone https://github.com/adhithiyan110/object_distance_detection.git
```
```
cd object_distance_detection
mkdir dnn
```
```
python3 measure_object_distance.py 
```
