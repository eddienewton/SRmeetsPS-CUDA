# SRmeetsPS

This repository contains CUDA implementation  for the paper:  
Songyou Peng, Bjoern Haefner, Yvain Queau and Daniel Cremers, "**[Depth Super-Resolution Meets Uncalibrated Photometric Stereo](https://arxiv.org/abs/1708.00411)**", In IEEE Conference on Computer Vision (ICCV) Workshop, 2017.

Original implementation: https://github.com/pengsongyou/SRmeetsPS

## Citation
If you use this code, please cite the paper:
```sh
@inproceedings{peng2017iccvw,
 author =  {Songyou Peng and Bjoern Haefner and Yvain Qu{\'e}au and Daniel Cremers},
 title = {{Depth Super-Resolution Meets Uncalibrated Photometric Stereo}},
 year = {2017},
 booktitle = {IEEE International Conference on Computer Vision (ICCV) Workshop},
}
```
Contact **Songyou Peng** [:envelope:](mailto:psy920710@gmail.com) for questions, comments and reporting bugs.

Command to run the makefile :
1. Create a build folder. CD into this folder
2. Run : cmake ./../SRmeetsPS-CUDA
3. Run : cmake --build .
4. Run : ./SRmeetsPS-CUDA
