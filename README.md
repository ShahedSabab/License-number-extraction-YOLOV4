# License-plate-extraction-YOLOV4
The objective is to extract the registration number/license plate number from different vehicle images. The task can be divided into 2 parts. First, detect the possible ROI(region of interest) - in this case it is the license plate of vehicles. Second, extract the letters and numbers from the detected region. To separate ROI from the images, object     

The original YOLOV4 model is pretrained with MS coco dataset. The model can detect objects in real-time.
<img src="detectedRaw.gif" width="100%">

# Performance with custom data:
<img src="performance.PNG" width="60%">

### Test 1:
<img src="/testimages/test1.jpg" width="80%">
<img src="/testimages/test1.PNG" width="60%">
### Test 2:
<img src="/testimages/test2.jpg" width="80%">
<img src="/testimages/test2.PNG" width="60%">
### Test 3:
<img src="/testimages/test3.jpg" width="80%">
<img src="/testimages/test3.PNG" width="60%">
### Test 4:
<img src="/testimages/test4.jpg" width="80%">
<img src="/testimages/test4.PNG" width="60%">
### Test 5:
<img src="/testimages/test5.jpg" width="80%">
<img src="/testimages/test5.PNG" width="60%">
### Test 6
<img src="/testimages/test6.jpg" width="80%">
<img src="/testimages/test6.PNG" width="60%">
