# Thinking in frequency: Face forgery detection by mining frequency-aware clues

<img alt="GitHub top language" src="https://img.shields.io/github/languages/top/Leminhbinh0209/F3Net?style=for-the-badge" height="25"  onmouseover="this.height='60'" onmouseout="this.height='25'" ><img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/Leminhbinh0209/F3Net?style=for-the-badge" height="25"><img alt="GitHub repo size" src="https://img.shields.io/github/repo-size/Leminhbinh0209/F3Net?style=for-the-badge" height="25">
<br />
*European Conference on Computer Vision 2020* <br /> 


This implementation is mainly based on the desciption in the [paper](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123570086.pdf) on top of XceptionNet. The inplementation has three models:
* **MixBlock**: Two-stream Collaborative Framework (@ block 7 and block 12). If you change the input image size, revise the ```width``` and ```height``` parameters in lines ```49``` and ```50```.
* **FAD**: Frequency-aware Decomposition
* **LFS**: Local Frequency Statistics


Source code is mainly referenced from this [repo](https://github.com/yyk-wew/F3Net). <br />
Download pre-trained XceptionNet from [here](http://data.lip6.fr/cadene/pretrainedmodels/xception-b5690688.pth).
#
*Star if you find it useful.* ⭐
