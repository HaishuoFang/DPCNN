### Deep Pyramid Convolutional Neural Networks for Text Categorization

This is the implementation of [DPCNN](http://www.aclweb.org/anthology/P17-1052) in tensorflow.

<div style="align: center">
![DPCNN](/img/dpcnn.png)
</div>

The key operation of this paper is 
- fixed feature map:250
- 2 stride downsampling which can compress effective information of long distance.
![pyramid](/img/pyramid.png)