# image-resizer

Used to rescale images.

I use this to rescale images that are going to be used on webpages.

## Usage:
```bash
#!/bin/bash

> virtualenv env
> source ./env/bin/activate
> cat requirements.txt
Pillow==7.2.0

> pip install -r requirements.txt

> python resize.py
resize.py <size_scaler> <file> ...

> python resize.py 0.5 image1.jpg image2.jpg
saving image1_width_height.jpg
saving image2_width_height.jpg
```
