# stb_python
Welcome to the stb_python repository.

This repository was created because we think that pillow is too slow at loading images. Thankfully a C header called stb_image.h exists, making loading images in the C programming language fast. This project aims to create a nice python library to interact with stb_image in a fast and memory-safe way. 

stb_python aims to support these image types:

- JPEG
- PNG
- TGA
- BMP
- PSD
- GIF
- HDR
- PIC
- PNM

This project heavily relies on [stb_image](https://github.com/nothings/stb/), so special thanks to the stb_image team!