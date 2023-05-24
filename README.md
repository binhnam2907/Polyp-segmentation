# Polyp Segmentation using UNET

Implementing polyp segmentation using the U-Net and CVC-612 dataset. <br/>

The dataset CVC-ClinicDB (CVC-612) is not complete. Download it from the <a href="https://polyp.grand-challenge.org/CVCClinicDB/"> Here </a> 
# CVC-ClinicDB (CVC-612)

The dataset contains the image extracted from the colonoscopy videos. These image contains different types polyps. The dataset also include the ground-truth for those images.
<br/><br/>
## Sample Image and Masks
 <img src="dataset/images/fine_3_10_fram.tif" height="356" width="356"> <img src="dataset/masks/fine_3_10_mask.tif" height="356" width="356"> 
 <img src="dataset/images/fine_3_11_fram.tif" height="356" width="356"> <img src="dataset/masks/fine_3_10_mask.tif" height="356" width="356"> 
 <img src="dataset/images/fine_3_12_fram.tif" height="356" width="356"> <img src="dataset/masks/fine_3_10_mask.tif" height="356" width="356"> 
 <br/>

## Results
The images given below are in the sequence: (1) Input Image, (2) Ground Truth, (3) Predicted Mask <br/><br/>
<img src="results/9.png">
<img src="results/13.png">
<img src="results/16.png">