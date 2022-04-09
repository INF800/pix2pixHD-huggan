# pix2pixHD-huggan

> Code heavily relies on https://github.com/NVIDIA/pix2pixHD. Thanks to cool developers at NVIDIA.


### Small pedestrian dataset (Penn-Fudan dataset) results

```
Number of training samples: 159
Number of test samples: 10
Hyperparamers: Not tuned. stopped training at 71st epoch.
```

Intermediate generations during training:

![](./assets/pedestrian_synthesis_training_71ep.gif)

Test sample results:

![](./assets/pedestrian_synthesis_test_159isto10.gif)

> **What is causing noisy BG but not so noisy person?**
> - Maybe side effect of small dataset
> - Maybe because semantic map is very sparse


### Deepglobe dataset

```
Number of images: 750:60
Original Resoultion: 2448x2448
Trained Resolution: 1024x1024
Epochs: 100+100
Hyperparamers: Not-tuned!
Device: A5000
Time Taken: 16Hrs
```

Test set results

![](assets/deepglobe_test_100ep.gif)

