# READFake Dataset: Reflection and Environment-Aware DeepFake Detection Dataset

## Introduction:
The **READFake** dataset contains 2,136 facial images in high and low resolution. 716 real facial images were collected from different datasets, including 565 images from Flickr Faces HQ (FFHQ) dataset, 69 images from Celeb-DF dataset, 53 images from FaceForensics++ dataset, and 29 images from DFDC dataset. We acquired 1,420 DeepFake facial images from various DeepFake detection datasets and human visual DeepFake generation tools, including 569 face synthesis DeepFake images from StyleGAN2 and StyleGAN3. Also, we collected 431 images from the Celeb-DF dataset, 369 images from the FaceForensics++ dataset with Face2Face and FaceSwap methods, and 51 images from the DFDC dataset. The **READFake** dataset contains DeepFake and real facial images in various resolutions with different environmental parameters, including illumination conditions, background colors, indoor or outdoor settings, face pose orientations, age, ethnicity, and appearances (e.g., wearing makeup and accessories). We annotated the **READFake** dataset with 3 different types:

  1. **The Body Specular Highlight (BSH) region annotation:** to identify highlight patterns from various reflective body regions. 
  2. **The Corneal Specular Highlights (CSH) region annotation:** to define the shapes and locations of CSH and classifies CSHs into right-reflection and left-reflection classes. 
  3. **The Image Annotation:** to identify the **image label (either Real or Fake)** , along with the **facial image environmental parameters (FIEP)**, including **indoor or outdoor (IO), light level (LL), and light strength (LS)**. 
  
The **READFake** dataset contains the 4272 annotated **CSH segmentation masks** for 2136 facial images (two eyes per facial image). In addition, 1779 images (83.30%) are labeled as indoor, and 357 images (16.70%) are labeled as outdoor. Furthermore it contains different LL classes (1414 mid images (66.20%), 438 low images (20.50%), and 284 high images (13.30%)).



