# READFake Dataset: Reflection and Environment-Aware DeepFake Detection Dataset

![READFake Dataset](https://github.com/READFake/READFake_Dataset/blob/main/anno101.jpg)

## Introduction:
The **READFake** dataset contains 2,136 facial images in high and low resolution. 716 real facial images were collected from different datasets, including 565 images from Flickr Faces HQ (FFHQ) dataset, 69 images from Celeb-DF dataset, 53 images from FaceForensics++ dataset, and 29 images from DFDC dataset. We acquired 1,420 DeepFake facial images from various DeepFake detection datasets and human visual DeepFake generation tools, including 569 face synthesis DeepFake images from StyleGAN2 and StyleGAN3. Also, we collected 431 images from the Celeb-DF dataset, 369 images from the FaceForensics++ dataset with Face2Face and FaceSwap methods, and 51 images from the DFDC dataset. The **READFake** dataset contains DeepFake and real facial images in various resolutions with different environmental parameters, including illumination conditions, background colors, indoor or outdoor settings, face pose orientations, age, ethnicity, and appearances (e.g., wearing makeup and accessories). We annotated the **READFake** dataset with 3 different types:

  1. **The Body Specular Highlight (BSH) region annotation:** to identify highlight patterns from various reflective body regions. 
  2. **The Corneal Specular Highlights (CSH) region annotation:** to define the shapes and locations of CSH and classifies CSHs into right-reflection and left-reflection classes. 
  3. **The Image Annotation:** to identify the **image label (either Real or Fake)** , along with the **facial image environmental parameters (FIEP)**, including **indoor or outdoor (IO), light level (LL), and light strength (LS)**. 
  
The **READFake** dataset contains the 4272 annotated **CSH segmentation masks** for 2136 facial images (two eyes per facial image). In addition, 1779 images (83.30%) are labeled as indoor, and 357 images (16.70%) are labeled as outdoor. Furthermore, it contains different LL classes, such as (1414 mid images (66.20%), 438 low images (20.50%), and 284 high images (13.30%)).

## Dataset Download: 

We have released the **READFake** dataset, including facial RGB images, the Body Specular Highlight (BSH) region annotation, the Corneal Specular Highlights (CSH) region annotation, the CSH images, and the The Image Annotation.

### Download links: 
[READFake_Dataset_CVPR2023.zip (930.4 MB)](https://drive.google.com/file/d/1HQr1weaDKohv4oRZFhzSQMw8bX3ZiQQQ/view?usp=sharing), to download full dataset.

## References: 

  [1]. Andreas Rossler, Davide Cozzolino, Luisa Verdoliva, Christian Riess, Justus Thies, and Matthias Nießner. Faceforensics++: Learning to detect manipulated facial images. In Proceedings of the IEEE/CVF International Conference on Computer Vision, pages 1–11, 2019.
  
  [2]. Yuezun Li, Xin Yang, Pu Sun, Honggang Qi, and Siwei Lyu. Celeb-df: A large-scale challenging dataset for deepfake forensics. In 2020 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), pages 3204–3213, 2020.
  
  [3]. Brian Dolhansky, Joanna Bitton, Ben Pflaum, Jikuo Lu, Russ Howes, Menglin Wang, and Cristian Canton Ferrer. The Deepfake Detection Challenge (DFDC) Dataset. arXiv preprint arXiv:2006.07397, 2020.
  
  [4]. Tero Karras, Samuli Laine, and Timo Aila. A style-based generator architecture for generative adversarial networks. In Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition, pages 4401–4410, 2019.
  
  [5]. Tero Karras, Samuli Laine, Miika Aittala, Janne Hellsten, Jaakko Lehtinen, and Timo Aila. Analyzing and improving the image quality of StyleGAN. In Proc. CVPR, 2020.
  
  [6]. Abhishek Dutta and Andrew Zisserman. The VIA annotation software for images, audio and video. In Proceedings of the 27th ACM International Conference on Multimedia, MM’19, New York, NY, USA, 2019. ACM.

