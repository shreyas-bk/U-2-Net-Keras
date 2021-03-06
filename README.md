# U-2-Net-Keras
Keras version of U2-Net: Going Deeper with Nested U-Structure for Salient Object Detection

*Please star if this was helpful*

# Link to colab notebook: [U-2-Netp Demonstration Colab-PyTorch2Keras.ipynb](https://colab.research.google.com/github/shreyas-bk/U-2-Net-Keras/blob/main/U_2_Netp_Demonstration_Colab_PyTorch2Keras.ipynb?authuser=1)

**Note: both models require GPU support as there are some issues during conversion for CPU only**

Download saved model (keras version of u2netp) from [Drive](https://drive.google.com/file/d/1HsA3zn4zKiyOCQlxDQZCdG8TS5C7daoe/view?usp=sharing)

Download saved model (keras version of u2net) from [Drive](https://drive.google.com/file/d/1y3LQSuxZcggilzMo82rPdGW9PMt-Lqam/view?usp=sharing)

# Inference
Inference code can be found in the notebook itself or minimal testing scripts can be found at [https://github.com/Voinic/u2net-keras](https://github.com/Voinic/u2net-keras) (includes GPU support for u2net_portrait inference as well)

TODO:
 - add rectified inference cell that doesn't use torch
 - add CPU supported weights trained on Keras model
