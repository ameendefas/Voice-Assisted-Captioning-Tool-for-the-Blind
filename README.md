# Voice-Assisted-Captioning-Tool-for-the-Blind
A voice assisted tool made by image processing and app development but unfortunately the file size is not accepting in git.
For training the model,Minimum GPU level- GeForce 2060 with 16 GB RAM.For testing,An Android device with minimum 4 GB RAM.
To deploy the trained model into an android application,TensorFlow Lite is used.
The existing Pytorch model is first converted to a TensorFlow model using Open Neural Network Exchange (ONNX).
Object Detection using YOLOv5 has been implemented and this can be incorporated to improve the quality of captions.
Optical Character Recognition
OCR using CRAFT (Character Recognition Awareness For Text detection and recognition) model has been implemented and using this, the text on the images can be identified.
