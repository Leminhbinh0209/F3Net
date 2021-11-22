# Thinking in frequency: Face forgery detection by mining frequency-aware clues
*European Conference on Computer Vision 2020* <br /> 
<br />
This implementation is mainly based on the desciption in the [paper](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123570086.pdf) on top of XceptionNet. The inplementation has three models:
* **MixBlock**: Two-stream Collaborative Framework (@ block 7 and block 12). If you change the input image size, revise the ```width``` and ```height``` parameters in lines ```49``` and ```50```.
* **FAD**: Frequency-aware Decomposition
* **LFS**: Local Frequency Statistics


Source code is mainly referenced from this [repo](https://github.com/yyk-wew/F3Net). <br />
Download pre-trained XceptionNet from [here](http://data.lip6.fr/cadene/pretrainedmodels/xception-b5690688.pth).
#
*Star if you find it useful.* ⭐
