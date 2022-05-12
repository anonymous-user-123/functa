# From data to functa: Your data point is a function and you should treat it like one

This README contains figures for the above paper.

## Figure 4
Meta-learned initialization + 4 gradient steps and target for test scene.
![](./figures/meta-learning-visualization-4-step-scene-gif.gif)

## Figure 7
Course of optimization for imputation of voxel from partial observation.

### From back
Partial observation    |  Imputation
:---------------------:|:---------------------:
![](./figures/voxel-imputation-back.png)  |  ![](./figures/voxel-imputation-front-from-back.gif)

### From front
Partial observation    |  Imputation
:---------------------:|:---------------------:
![](./figures/voxel-imputation-front.png)  |  ![](./figures/voxel-imputation-back-from-front.gif)

### From left
Partial observation    |  Imputation
:---------------------:|:---------------------:
![](./figures/voxel-imputation-left.png)  |  ![](./figures/voxel-imputation-right-from-left.gif)

### From lidar scan
Partial observation    |  Imputation
:---------------------:|:---------------------:
![](./figures/voxel-imputation-lidar-x.png)  |  ![](./figures/voxel-imputation-lidar-x.gif)


## Figure 9
Uncurated samples from DDPM (diffusion) trained on 64-dim modulations of SRN-cars.

![](./figures/car-flow-samples-512-gif.gif)

## Figure 10
Latent interpolation between two car scenes with moving pose.

![](./figures/car-flow-latent-interpolation-512-gif.gif)

## Figure 11
Novel view synthesis from occluded view.
Occluded view        |  Ground truth       |Inferred             | No prior
:-------------------:|:-------------------:|:-------------------:|:-------------------:
![](./figures/novel-view-synthesis-car-masked.png) | ![](./figures/novel-view-synthesis-car-target.gif) | ![](./figures/novel-view-synthesis-car-mask-gif.gif)| ![](./figures/novel-view-synthesis-car-mask-no-prior-gif.gif)


## Figure 12
Uncurated samples from flow trained on 256-dim modulations on ERA-5 temperature data.
![](./figures/era5-flow-samples-256-gif.gif)

## Figure 26
Additional voxel imputation results.
Partial observation    |  Imputation
:---------------------:|:---------------------:
![](./figures/chair2.png)  |  ![](./figures/chair2-imputation-gif.gif)
![](./figures/chair3.png)  |  ![](./figures/chair3-imputation-gif.gif)
![](./figures/chair4.png)  |  ![](./figures/chair4-imputation-gif.gif)
![](./figures/chair5.png)  |  ![](./figures/chair5-imputation-gif.gif)

## Figure 27
Additional novel view synthesis results.
Occluded view        |  Ground truth       |Inferred             | No prior
:-------------------:|:-------------------:|:-------------------:|:-------------------:
![](./figures/car3-masked.png) | ![](./figures/car3-target-gif.gif) | ![](./figures/car3-inferred-gif.gif)| ![](./figures/car3-no-prior-gif.gif)
![](./figures/car4-masked.png) | ![](./figures/car4-target-gif.gif) | ![](./figures/car4-inferred-gif.gif)| ![](./figures/car4-no-prior-gif.gif)
![](./figures/car5-masked.png) | ![](./figures/car5-target-gif.gif) | ![](./figures/car5-inferred-gif.gif)| ![](./figures/car5-no-prior-gif.gif)
![](./figures/car6-masked.png) | ![](./figures/car6-target-gif.gif) | ![](./figures/car6-inferred-gif.gif)| ![](./figures/car6-no-prior-gif.gif)


