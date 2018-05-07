# webcam_toolbox2-for-measuring-and-recording-on-the-machine

By using the code, you can measure/record a Heart signal and its video clip through camera of PC.
The code is very easy and intuitive. Hope you get a help when you get a chance to interest it in implementing heart monitoring system from a face.

The whole of this code is based on python.
And as a development environment to do this, I used "Jupyter Lab" and "Anaconda".

Whenever you run this code, several outcomes (uncompressed ROI faces, processed signal) you are going to have at your directory.
In order to analyze recorded images by 2D signal processing, you can simply import these files from your directory.

```
# Simple example for data import
filename = 'C:/Users/ChungkiLee/Documents/GitHub/webcam/previewimgs/outpy2018_05_06_15_12_14.out'

my_shelf = shelve.open(filename)
for key in my_shelf:
    globals()[key]=my_shelf[key]
my_shelf.close()
```

<img src="https://github.com/chungbrain/webcam_toolbox2-for-measuring-and-recording-on-the-machine/blob/master/2018-05-07_16-04-04.png" width="720"> 

Plus, you also get compressed video clip (.mp4 format) shown as below.

<img src="https://github.com/chungbrain/webcam_toolbox2-for-measuring-and-recording-on-the-machine/blob/master/2018-05-07_15-41-19.png" width="720"> 

