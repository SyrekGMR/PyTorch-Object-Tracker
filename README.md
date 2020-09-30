# PyTorch-Object-Tracker [ONGOING]
<p align="center">
  <img src="Assets/Detector.jpg" width="400" height="600" /></img>
</p>
          
<br><br>
A project looking at implementing an object tracking mechanism compatible with any arbitrary object detector which produces bounding box coordinates and confidence scores. The project is base in PyTorch, utilising some of the currently leading models within the field of object detection.
<br><br>
<h2> Progress Update </h2>
<p align="center">
  <img src="Assets/update.gif"/></img>
</p>
Using an EfficientDet model, it is possible to obtain good detections at medium to close range, however work is required to threshold the more distant detections which appear for individual frames. The tracking algoirthm still requires tweaking to allow tracking over longer timescale and at various distances and scales.
<br><br>
<h2>This is an ongoing project</h2>
<h1>Project Roadmap</h1>
<br>

- [x] Object Detector Model
- [x] Data Pre-processing pipeline
- [x] Object Tracking Algorithm
- [x] Video Streaming Pipeline
- [ ] Model / Algorithm Tweaking
- [ ] Code Clean-Up and Deployment
