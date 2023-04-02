# Super-ResolutionUnet


Perform super resolution using MODIS LST images at 1km and NDVI images at 250m to generate an LST output at 250m without having the ground truth data and using the gradient information of the NDVI.  

<p float="left">
  <img src="./example_images/final_lst.png" width="500" />
  <img src="./example_images/final_aster.png" width="500" /> 
</p>

<p align="center">
  <em>Output of the model (left) and ground truth (right)</em>
</p>

<p float="left">
  <img src="./example_images/interpolated_lst.png" width="300" />
  <img src="./example_images/interpolated_ndvi.png" width="300" />
  <img src="./example_images/grad_output_ndvi_normalized.png" width="300" />
</p>

<p align="center">
  <em>Input LST image (left), input NDVI image (middle) and normalized NDVI gradient (right)</em>
</p>



