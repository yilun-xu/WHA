# Color Mapping Functions For HDR Panorama Imaging: Weighted Histogram Averaging

## Abstract
It is challenging to stitch multiple images with different exposures due to possible color distortion and loss of details in the brightest and darkest regions of input images. In this paper, a novel color mapping algorithm is first proposed by introducing a new concept of weighted histogram averaging (WHA). The proposed WHA algorithm leverages the correspondence between the histogram bins of two images which are built up by using the non-decreasing property of the color mapping functions (CMFs). The WHA algorithm is then adopted to synthesize a set of differently exposed panorama images. The intermediate panorama images are finally fused via a state-of-the-art multi-scale exposure fusion (MEF) algorithm to produce the final panorama image. Extensive experiments indicate that the proposed WHA algorithm significantly surpasses the related state-of-the-art color mapping methods. The proposed high dynamic range (HDR) stitching algorithm based on MEF also preserves details in the brightest and darkest regions of the input images well. The related materials will be publicly accessible at this https URL for reproducible research.

## Code
the implementation code will be open source after the journal is accepted.

## Paper Download Link
https://arxiv.org/abs/2111.07283

## Citation
If you find this code or dataset is helpful in your research, please cite:
```
@article{xu2021color,
  title={Color Mapping Functions For HDR Panorama Imaging: Weighted Histogram Averaging},
  author={Xu, Yilun and Li, Zhengguo and Chen, Weihai and Wen, Changyun},
  journal={arXiv preprint arXiv:2111.07283},
  year={2021}
}
```

## Contact
If you have any questions, feel free to E-mail me via: `yilunxu_buaa@163.com`

## License
The code is released under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International Public License for Noncommercial use only. Any commercial use should get formal permission first.
