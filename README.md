# EZImage




using AIEZ;

#Original Image
```
Image OriginImg = Image.FromFile("C://demo.png");
```

#New EZImage
```
var EzImage = new EZImages();
```


#Image Conversion to byte
```
var Imgbyte = EzImage.ImageToByte(img,System.Drawing.Imaging.ImageFormat.Png);
```

#Byte Conversion to Image
```
var Img = EzImage.ByteToImage(Imgbyte);
Img.Save("FullPath");
```

#Image Resize
```
EzImage.Image = Img;
var NewSizeImg = EzImage.Resize(50,50) ;
NewSizeImg .Save("FullPath");
 
```
