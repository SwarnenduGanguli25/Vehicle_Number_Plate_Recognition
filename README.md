# Vehicle_Number_Plate_Recognition

*This project is basically divided into 3 major parts*:-
<br>

**1. DETECTION:-** In this part, we used YOLOv3 with darknet configuration to detect the license plates with pre-trained weights and model and then store the coordinates in a json file.
<br>

**2. CROPPING:-** Here, we cropped out the license plate from the rest of the image by deducing border coordinates from the json file.
<br>

**3. RECOGNITION:-** This is the final part where we used Microsoft Computer Vision API for recognizing the text from the license plates.
<br>

All the files were not able to be uploaded due to large size. So, here are the links which will help you:
<br>

**Training Dataset-** https://drive.google.com/file/d/1t20-WpJWvon2o7MdoS88FyBw8yYrRKln/view
<!-- -->
**Test Dataset-** https://drive.google.com/file/d/1as5wGXC3M4ErAYn9Q0vxeLPwlS5JInNV/view
<br>

**Initial Weights(To be used in YOLO)-** https://drive.google.com/file/d/1OBNcSfNH53HHCEZbfIRsCygDCevS8NaJ/view
<br>

**Trained Weights(To be used in YOLO)-** https://drive.google.com/file/d/1I3JY2-0mr1wNz7ifEzxct8GJyxEy-doL/view
<br>

Also, you need to GIT CLONE(For Darknet): https://github.com/AlexeyAB/darknet.git
<br>

**Config File-** https://drive.google.com/file/d/1LUn13-uzHkPDaCjnNvJwiDnUWYROZeBB/view?usp=sharing  
**Train.txt File-** https://drive.google.com/file/d/1GR4MAlj4l5RrqqXvCrCMwRKmc0Qz13NK/view?usp=sharing  
**Valid.txt File-** https://drive.google.com/file/d/1do-En6hXvgPv2JG4-g1ro5Dz8hlYCx9R/view?usp=sharing  
**obj.data File-** https://drive.google.com/file/d/1dr9hrp6GlBih7b7Nl8orf0nY3yN8OdFV/view?usp=sharing  
**obj.name File-** https://drive.google.com/file/d/1XMeEWbGjHvBo7m-wSIeNM03n0UNioTuQ/view?usp=sharing
