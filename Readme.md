# Real-time Drowsiness Detection using YOLOv5
## This repository demonstrates the real-time detection of drowsiness in people using YOLOv5.

## Function
#### The code performs the following tasks:

1- Install and Import Dependencies: Necessary libraries including PyTorch, OpenCV, and Matplotlib are installed and imported.

2- Load Pre-trained Model: YOLOv5 pre-trained model is loaded using Torch Hub.

3- Make Detections with Images: Object detection is performed on a static image with pre-trained YOLOv5 model. Results are visualized using Matplotlib.

4- Real-time Drowsiness Detection: Real-time detection of drowsiness in people is performed using a live webcam feed. YOLOv5 model is utilized to detect faces and eyes, and drowsiness is inferred based on the analysis of eye states.

5- Train from Scratch: Custom dataset is collected from a webcam feed and labeled using the LabelImg tool. YOLOv5 is trained on the custom dataset with specified configurations.

6- Load Custom Model: Custom-trained YOLOv5 model is loaded and used for both static image and real-time webcam detections.

#### For detailed implementation and usage instructions, please refer to the code comments and documentation within the respective files.

### This README provides an overview of the code functionality, focusing on the real-time detection of drowsiness using YOLOv5. Further details can be found within the code itself.
