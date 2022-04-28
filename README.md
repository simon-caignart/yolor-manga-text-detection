# Text detection on manga pages with YOLOR

I trained the **YOLOR [1]** algorithm on the **Manga109 dataset [2]** to detect texts on manga pages.

## Train and test it.
You can use the ``yolor.ipynb`` file to test the model or train it with your own dataset.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/SimonCaignart/yolor-manga-text-detection/blob/main/yolor.ipynb)

## Dataset
I used the **Manga109 dataset [2]** to train my model. If you wish to download it, you can send an application via [this form]( https://docs.google.com/forms/d/e/1FAIpQLSefUGHUlkDfYlnOKLZlBqRtqlhmZWmhL1_NBfZ24zHOeCoguA/viewform). I used [Roboflow](https://roboflow.com/) to manage my dataset (split it, apply preprocessing and augmentations), and to easily download it to my python notebook.

## Trained weights
You can download the trained weights [here](https://drive.google.com/file/d/1yEN1xPaFNhnbzyUqomABDlm3c50lXv3W/view?usp=sharing). This is the best overall over 100 epochs of training.

## References

<a id="1">[1]</a> 
Wang, Chien-Yao & Yeh, I-Hau & Liao, Hong-yuan. 
You Only Learn One Representation: Unified Network for Multiple Tasks.
2021

<a id="2">[2]</a> 
Kiyoharu Aizawa and Azuma Fujimoto and Atsushi Otsubo and Toru Ogawa and Yusuke Matsui and Koki Tsubota and Hikaru Ikuta. 
Building a Manga Dataset ``Manga109'' with Annotations for Multimedia Applications.
IEEE MultiMedia, 27, 2, 8--18, 2020


