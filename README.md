# Dense Feature
In this package, you find MATLAB code for extracting dense Color Histogram and dense SIFT feature from a given image. 

## Remarks
- The core function (sp_dense_sift.m) comes from Scenes/Objects classification toolbox http://www.mathworks.com/matlabcentral/fileexchange/29800-scenesobjects-classification-toolbox
- The core function (sp_dense_color.m) is a modified MATLAB version of the denseCOLOR.cpp in the toolbox without loss of computation efficiency. 
- These low-level visual features are used in following research works, please kindly cite our work in your publications if it helps your research. 
- [salience_reid](https://github.com/Robert0812/salience_reid) 

	@inproceedings{zhao2013unsupervised,
 		title = {Unsupervised Salience Learning for Person Re-identification},
 		author={Zhao, Rui and Ouyang, Wanli and Wang, Xiaogang},
 		booktitle = {IEEE Conference on Computer Vision and Pattern Recognition (CVPR)},
 		year = {2013}
	}
	
- [salience_match](https://github.com/Robert0812/salience_match)

  	@inproceedings{zhao2013person,
 		title = {Person Re-identification by Salience Matching},
 		author={Zhao, Rui and Ouyang, Wanli and Wang, Xiaogang},
 		booktitle = {IEEE International Conference on Computer Vision (ICCV)},
 		year = {2013}
	}

## Acknowledgement
- [Sebastien Paris](http://www.mathworks.com/matlabcentral/fileexchange/authors/13308)'s submission in MATLAB FileExchange inspired this package.   


