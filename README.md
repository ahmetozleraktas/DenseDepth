## [High Quality Monocular Depth Estimation via Transfer Learning (arXiv 2018)](https://arxiv.org/abs/1812.11941)
[Ibraheem Alhashim](https://ialhashim.github.io/) and Peter Wonka

## EHB328 Project
You can check the `template.ipynb` file for the code used in the project. Any indoor room with size 640x480 can be used as input. The output is a depth map of the half size.


## Pre-trained Model
* [NYU Depth V2](https://drive.google.com/file/d/19dfvGvDfCRYaqxVKypp1fRHwK7XtSjVu/view?usp=sharing) (165 MB)


## Demos
* After downloading the pre-trained model (nyu.h5), run `python test.py`. You should see a montage of images with their estimated depth maps.

## Evaluation
* Download, but don't extract, the ground truth test data from [here](https://s3-eu-west-1.amazonaws.com/densedepth/nyu_test.zip) (1.4 GB). Then simply run `python evaluate.py`.

## Reference
Corresponding paper to cite:
```
@article{Alhashim2018,
  author    = {Ibraheem Alhashim and Peter Wonka},
  title     = {High Quality Monocular Depth Estimation via Transfer Learning},
  journal   = {arXiv e-prints},
  volume    = {abs/1812.11941},
  year      = {2018},
  url       = {https://arxiv.org/abs/1812.11941},
  eid       = {arXiv:1812.11941},
  eprint    = {1812.11941}
}
```
