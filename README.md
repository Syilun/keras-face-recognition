# Face Recognition and more with KERAS

#### Keras implementation of the paper: [FaceNet: A Unified Embedding for Face Recognition and Clusterin](https://arxiv.org/abs/1503.03832)

![alt text](https://github.com/Golbstein/keras-face-recognition/blob/master/assets/face_reco.JPG)


* ## Dataset: 
  - **[CelebA Dataset](http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html)**
  - Link for downloading face images: [img_align_celeba](https://drive.google.com/file/d/0B7EVK8r0v71pZjFTYXZWM3FlRnM/view?usp=sharing)

* ## Dependencies
  - **Keras 2 (tensorflow backend)**
  - **open-cv**
  - **tqdm**
  - **pandas**
  
* ## Model
  - Feature extractor model: [Xception](https://arxiv.org/pdf/1610.02357.pdf)
  - Embedding model: FaceNet
  
  ![alt text](https://github.com/Golbstein/keras-face-recognition/blob/master/assets/openface.jpg)

* ## Loss
  **[Triplet Loss](https://towardsdatascience.com/lossless-triplet-loss-7e932f990b24)** with cosine similarity
  
  ![alt text](https://github.com/Golbstein/keras-face-recognition/blob/master/assets/obama.png)
  ![alt text](https://github.com/Golbstein/keras-face-recognition/blob/master/assets/loss.JPG)
  
  Where *f_i* is the embedding vector of image *i*
  
- [x] Recognize celebrities with trained FaceNet model
- [x] Find out your Doppelgänger
- [ ] Beauty test
