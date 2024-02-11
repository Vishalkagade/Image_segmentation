# Drivable Area Detection using Image Segmentation
The aim of project is to predict drivable area in an image using Unet.
![project_output2-ezgif com-video-to-gif-converter](https://github.com/Vishalkagade/Image_segmentation/assets/105672962/1b307f1f-ce56-47e9-8455-3d67aa672e3f)

## Model
<img width="480" alt="image" src="https://github.com/Vishalkagade/Image_segmentation/assets/105672962/48d1c9a4-dc8d-4b47-a605-a16e295eba53">

Model can be downloaded from here https://drive.google.com/file/d/1QZbHF8O6NgpbDaN2fDe40h0L1J088pln/view?usp=sharing


## Dataset
The dataset can be found in the course at this address. It's in Pickle format and contains 3,000 images and labels downloaded from Berkeley Deep Drive Dataset.Then this dataset is further increased to more 3000 images using data augmentation. 

Dataset download Link : [https://drive.google.com/file/d/14CLaT5mipIQlKcNQNlnV5B6hu6ziqYBj/view?usp=sharing]

<img width="1020" alt="image" src="https://github.com/Vishalkagade/Image_segmentation/assets/105672962/557eb1b8-99dd-4882-8934-eed10b7d2eb2">

## Test

To test the result please refer ipynb file attached and trained model.
## Results
<img width="539" alt="image" src="https://github.com/Vishalkagade/Image_segmentation/assets/105672962/0a31fcc7-a78f-4b2b-a949-b145ef131ae1">

The mask and original image is blended using cv2.bitwise_and technique.

<img width="533" alt="image" src="https://github.com/Vishalkagade/Image_segmentation/assets/105672962/f49e17ba-e323-41af-9714-563f672319c1">

![1b6f4b03-b5c8-423c-8f98-293f838c0b34-ezgif com-video-to-gif-converter](https://github.com/Vishalkagade/Image_segmentation/assets/105672962/be24e36f-dfec-44a0-b27a-08d917f7c879)

## references
Unet: https://arxiv.org/abs/1505.04597

https://courses.thinkautonomous.ai/image-segmentation


