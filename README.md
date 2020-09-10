# MyXUIControls
XUI Controls (b4a, b4i, b4j) - Tested on an old android 4.4 500mb phone with great performance.

![GUI SCREENSHOT](https://raw.githubusercontent.com/alejandrojavierm/MyXUIControls/master/ImgDoc/Sh_19-07-19A.png)
![GUI SCREENSHOT](https://raw.githubusercontent.com/alejandrojavierm/MyXUIControls/master/ImgDoc/XUIImgButton-04-08-2019.png)
![GUI SCREENSHOT](https://raw.githubusercontent.com/alejandrojavierm/MyXUIControls/master/ImgDoc/XUILabel-04-08-2019.png)
![GUI SCREENSHOT](https://raw.githubusercontent.com/alejandrojavierm/MyXUIControls/master/ImgDoc/OptionBtn.png)

# Controls
* XUIImageButton
* XUIImageToggleButton
* XUIAutoresizeLabel
* XUIOptionSwitch

# Documentation

This classes handle the label and image sizes, plus handle the spaces and margins.

### XUIImageBotton and XUIImageTogleBotton controls haves this features:

Image: the filename to be loaded from the resources

Image orientation:
* LEFT: classic <image> <space> <label> on the left, its have an
* CENTER: the same than left but on the center
* BOTTOM: the image are top of the label, both are centered
  
Label orientation:
* LEFT
* CENTER
* RIGHT

Events:
* CLICK

#### XUIImageBotton features:
* Pressed Color
* Delay from base to pressed color
#### XUIImageTogleBotton features:
* Pressed Color
* IsPressed (propety)
* PressedImageFileName: the filename of the image to be loaded from the resources when its pressed.

### XUIAutoresizeLabel features:
* Auto Resize
