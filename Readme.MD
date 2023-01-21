Phase 1:
1. Individual Function calls have been just after every function definition. For ex. the function call for gabor() function is just the next block to it. 
2. To directly get the Pb-lite output, directly run the pb_lite() function call, after running the previous function cells. 
3. To get results for different images, just change the image number in get_image(), get_sobel(),get_canny() functions.


Phase 2:
1. Training-
BaseClass-uncomment line 229 in Train block,comment other models. 
Improved- uncomment line 230 in Train block,comment other models.
Resnet- uncomment line 232 in Train block,comment other models.
Densenet- uncomment line 233 in Train block,comment other models.
Resnext- uncomment line 234 in Train block,comment other models.

2. Testing- 
BaseClass-uncomment line 70 in Test block,comment other models. Also uncomment line 154, while commenting other modelpaths. 
Improved- uncomment line 75 in Test block,comment other models.Also uncomment line 153, while commenting other modelpaths. 
Resnet- uncomment line 68 in Test block,comment other models.Also uncomment line 152, while commenting other modelpaths. 
Densenet- uncomment line 67 in Test block,comment other models.Also uncomment line 151, while commenting other modelpaths. 
Resnext- uncomment line 70 in Test block,comment other models.Also uncomment line 150, while commenting other modelpaths. 
