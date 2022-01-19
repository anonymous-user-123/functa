# From data to functa: Your data point is a function and you should treat it like one

This README contains figures for the above paper.

## Figure 4
Meta-learned initialization + 4 gradient steps and target for test scene.
![](./figures/meta-learning-visualization-4-step-scene-gif.gif)

## Figure 8
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


## Figure 10
Uncurated samples from flow trained on 512-dim modulations of SRN-cars.

![](./figures/car-flow-samples-512-gif.gif)

## Figure 11
Latent interpolation between two car scenes with moving pose.

![](./figures/car-flow-latent-interpolation-512-gif.gif)

## Figure 12
Novel view synthesis from occluded view.
Occluded view        |  Ground truth       |Inferred             | No prior
:-------------------:|:-------------------:|:-------------------:|:-------------------:
![](./figures/novel-view-synthesis-car-masked.png) | ![](./figures/novel-view-synthesis-car-target.gif) | ![](./figures/novel-view-synthesis-car-mask-gif.gif)| ![](./figures/novel-view-synthesis-car-mask-no-prior-gif.gif)


## Figure 13
Uncurated samples from flow trained on 256-dim modulations on ERA-5 temperature data.
![](./figures/era5-flow-samples-256-gif.gif)


