# Mask Detection using InceptionV3

* Inception-V3 : Inception-V3 has the best results(98%) compared to MobileNetV2 and NASNetMobile.It is a slightly more complex model but when the pre-trained it can be converted into TF-lite and used on EDGE devices.

<div>
<img src="https://github.com/sidgan22/MaskDetection/blob/master/images/Inception-plot.png" data-canonical-src="https://github.com/sidgan22/MaskDetection/blob/master/images/Inception-plot.png" width="500" height="400" />
<img src="https://github.com/sidgan22/MaskDetection/blob/master/images/Inception.PNG" data-canonical-src="https://github.com/sidgan22/MaskDetection/blob/master/images/Inception.PNG" width="450" height="400" />
</div>
  
* NASNetMobile : NASNetMobile is light-weight and has a precision of 97%, it is also computationally efficient and thus makes it easier to deploy the model to embedded systems (Raspberry Pi, Google Coral, etc.).
    
<div>
<img src="https://github.com/sidgan22/MaskDetection/blob/master/images/NASNetMobile-plot.png" data-canonical-src="https://github.com/sidgan22/MaskDetection/blob/master/images/NASNetMobile-plot.png" width="500" height="400" />
<img src="https://github.com/sidgan22/MaskDetection/blob/master/images/NASNET.PNG" data-canonical-src="https://github.com/sidgan22/MaskDetection/blob/master/images/NASNET.PNG" width="450" height="400" />
</div>

* MobileNet-V2 : The model has an accuracy of 94%, and since we used the MobileNetV2 architecture, it’s also computationally efficient and thus makes it easier to deploy the model to embedded systems (Raspberry Pi, Google Coral, etc.).
  
<div>
<img src="https://github.com/sidgan22/MaskDetection/blob/master/images/MobileNetV2-plot.png" data-canonical-src="https://github.com/sidgan22/MaskDetection/blob/master/images/MobileNetV2-plot.png" width="500" height="400" />
<img src="https://github.com/sidgan22/MaskDetection/blob/master/images/MobileNetV2.PNG" data-canonical-src="https://github.com/sidgan22/MaskDetection/blob/master/images/MobileNetV2.PNG" width="450" height="400" />
</div>
  
This system can therefore be used in real-time applications which require face-mask detection for safety purposes due to the outbreak of Covid-19. This project can be integrated with embedded systems for application in airports, railway stations, offices, schools, and public places to ensure that public safety guidelines are followed.

