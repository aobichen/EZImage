# EZImage

#圖片轉位元組

#位元組轉圖片

#圖片尺寸縮放

#圖片儲存



using AIEZ;

#Original Image
```ruby
Image OriginImg = Image.FromFile("C://demo.png");
```

#New EZImage
```
var EzImage = new EZImages();
```


#Image Conversion to byte
```ruby
var Imgbyte = EzImage.ImageToByte(img,System.Drawing.Imaging.ImageFormat.Png);
```

#Byte Conversion to Image
```ruby
var Img = EzImage.ByteToImage(Imgbyte);
Img.Save("FullPath");
```

#Image Resize
```ruby
EzImage.Image = Img;
var NewSizeImg = EzImage.Resize(50,50) ;
NewSizeImg .Save("FullPath");
 
```
