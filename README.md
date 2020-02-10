# Image classification with Tensorflow

## What and why

Demo for Cinia techday 21.11.2019

## How to run

Install docker. Build

```
docker build -t cinia/tensorflow-demo .
```

and run

```
docker run -p 8888:8888 -e JUPYTER_ENABLE_LAB=yes -v "$PWD"/notebooks:/home/jovyan/notebooks  \
  --user $(id -u) --group-add users cinia/tensorflow-demo
```

## Acknowledgements

Based on Google's image classification tutorial
https://raw.githubusercontent.com/tensorflow/hub/master/examples/image_retraining/retrain.py
https://raw.githubusercontent.com/tensorflow/tensorflow/master/tensorflow/examples/label_image/label_image.py

and course TIES4911 Deep-Learning for Cognitive Computing for Developers at University of Jyväskylä demo excercises.

## Links to some Colab notebooks

Image classification (same as this but in colab)
https://colab.research.google.com/drive/1k1I6Um9UPUfP1PCeb3LtjM4CYYnJutDI

Object detection
https://colab.research.google.com/drive/14xAWX3F84Li8DDUeZBOpZPzmkVRr3i_1

Tesseract OCR
https://colab.research.google.com/drive/1AqRULUbHjoEX5EZYBFOpcb6CKqWKySCc

Style transfer
https://colab.research.google.com/drive/1DxAKEkHLWOtwIUMREM0c3U-lmhJFzYj7
