### Challenge
This project designs an intelligent image-based trash bin, involving deep learning models for garbage classification, single-chip microcomputer communication, and mechanical module design for classification. 
### Method
The project builds a deep learning model of YOLOv3 for object detection. The detected class labels are transmitted to the Raspberry Pi via socket protocols. The Raspberry Pi then forwards the integrated information to Arduino, which drives the trash bin’s base motor to rotate and control the trash bin’s panel servo motor to rotate, thereby depositing the garbage into the correct classification area.

https://github.com/user-attachments/assets/261e531d-5cab-4284-83b5-4c3fc14c8041

