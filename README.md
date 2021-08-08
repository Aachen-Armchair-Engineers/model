# DoorDetect Training and Export
This repository contains code to train, export and test a tensorflow object detection API model, specifically for the [DoorDetect-dataset](https://github.com/MiguelARD/DoorDetect-Dataset).
Additionally there is code to convert/compile the model to a `.blob`-file for the OAK-devices.

There are three jupyter notebooks:
1. [Train and Create Doordetect Model](train_model.ipynp)
2. [Object Detection From TF2 Saved Model](test_model.ipynp)
3. [Create a binary blob for an OAK-device from an object detection API model](create_blob.ipynp)
