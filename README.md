# Vehicle Number Plate Detection System


This security system can be setup in various firm infrastructure, parking garages and
also in residential parking areas. This constructs to be set as an automated License
Plate detection system for every vehicle entering the area and maintaining a record
of them.


A Database implementation is being built in the near future, where the license plates
detection shall be cross validated against the database to detect any new vehicles
from other than the registered ones.


This version of coded or trained using the built-in har-cascade classifier in OpenCv
module python and text extraction is done using the module Pytesseract. The next
version shall be a bettered in terms of accuracy as it shall be constructed using
YOLOv3. The dataset for YOLOv3 and the mobile version of Pre-trained model on
COCO dataset is available. What remains is the implementation.
Data-Images: Data of cars, their corresponding license plates constructed using
object detection and their labels( dimension os license plates and class = 0 by
default).

`Indian_license_plate.xml` : cascaded file for indian license plates <br>
`Test_on_Image` : A sample code for understanding how every frame image extracted <br>
from the video is processed to generate the license plate numbers.
`Detect` : The file to detect license plates from a video file.
Paste the file path in the variable cap. <br>
`Dataset_builder` : For next version of YOLOv3, this dataset was constructed to be fed
into the pretrained mobile model. <br>
`Ssd_mobilenet_v3_large_coco_2019_08_14.tar` : Pretrained YOLOv3 model on
coco-dataset. <br>
