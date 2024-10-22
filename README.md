# YOLOV3-Detection-of-Truck-Vehicle-Types
You only look once (YOLO) is a state-of-the-art, real-time object detection system. YOLOV3 is extremely fast and accurate compared with other algorithms, such as R_CNN, RetinaNet etc. It uses Darknet-53 as the backbone network and uses three scale predictions. 
In this Notebook a YoloV3 model was trained using Darknet by transfer learning with GPU on Colab. 
Collect 8 classes samples (480 images): USPS Truck, UPS Truck, Ambulance, Fire Truck, FedEx Truck, Bus, Police Car and Other Vehicle. 
Collect negative samples (100) with objects that we do not want to detect, such as streets, pedestrian, buildings, traffic lights, etc. 
Train, Validation and Test sample preparation; Sample labeling using LabelImg. 
Speeding up training by using Fine Tune technique. 
Install Darknet and cuDNN; compile Darknet, configuration training file. 
Negative samples improved model performance. 
Inference 8 classes Truck/Vehicle images correctly; Inference videos.
