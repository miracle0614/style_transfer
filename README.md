# SaoImage

### Introduction

This project is used for **image style transfer**

### Environment

- Windows 10
- Python 3.6
- Tensorflow 1.2.1
- Flask 0.12.2

### Start

```
cd web_IST
python35 app.py
```

### Attention

1. The content image must be stored in `static/contents/`
2. The style image must be stored in `static/styles/`
3. The mixed images will be stored in `static/outputs/<contentName_styleName/>` , and a gif reflected the process will be  stored in `static/gif/`

### Help

1. Choose your content image and style image.

   ![](./static/pic/1.jpg)

2. Input a train time, make sure that it should not be too lagre, or it will take a long time.

   ![](./static/pic/2.jpg)

3. Wait for your result.

   ![](./static/pic/3.jpg)
