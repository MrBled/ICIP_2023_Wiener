# Pushing the Limits of the Wiener Filter 
ICIP 2023 Supplementary Material


## STD Prediction-Net Diagram
<p align="center">
  <img src=draw_uio_final.drawio_correctlegend.png>
</p>

*STD Prediction-Net Architecture and Training Pipeline. Diagram represents the 4x16 CNN variant.*

## Wiener Fine Tuning Network
<p align="center">
  <img src=wiener_diagram.png>
</p>

*22k params. add omegas, add frequency domain, add "predicted/final H at end". reshape 1 and reshape 2 are mixed up.*
## Complete Results for all STD Prediction-Net architectures.

<p align="center">
  <img src=std_nets.png>
</p>

*Complete table of result for all trained STD prediction-nets, with number of trainable parameters included. The first row denotes a Wiener filter with manually input global standard deviation of $\sigma = 10$*

<p align="center">
  <img src=mean_im_with_gt.png>
</p>

*Final Results for all DC-offset estimation methods. need to include params...*

## Denoising Results
<p align="center">
  <img src=mosaic_1-1.png>
</p>

