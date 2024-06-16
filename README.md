# thumbmailer
Generate thumbnail images from various types of files. 

You need to install a few python modules and binaries:
```bash
pip install pillow Wand nbformat opencv-python openpyxl python-pptx python-docx 
brew install freetype imagemagick
```

## TODO
- Need to find a simple way to convert text that mixes Unicode and emoji into an image. Depending on the font used, the image conversion supports either English+emoji (using Symbola) or only Unicode without emoji (using various fonts such as D2Coding).