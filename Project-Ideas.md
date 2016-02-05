# Project Ideas...

## 1. Recommendation System for Process-Property Information

#### Dataset
Process information and property measurements for 218 devices in the literature. There are more papers that could be added as well.

#### Challenge
Use a recommendation system / regression model that can handle mixed datatypes to make best guesses at missing process information.

#### Potential Difficulties
Validation may require contacting authors, and the information may not even be known in this case, or the author may be gone.

## 2. Supervised Fiber Segmentation

#### Dataset
43 images and ~20,000 segmented fibers. This ammounts to ~10,000,000 image pixels that have been classified by an "oracle teacher".

#### Challenge
Identify the minimum number of training fibers needed to train an automatic segmentation algorithm that matches oracle performance.

#### Potential Difficulties
The classification space is both binary (fiber/not fiber) and continuous (orientation). Also, the oracle teacher also provides information on which pixels belong to the same fiber, so that fiber length can be measured. So the next level of this project would be to perform a combined classification/clustering of pixels. 

## 3. Extraction of Common Order Parameters from Spatial Statistics

#### Dataset
The same 43 images as above, but the microstructures have already been binarized including orientation information.

#### Challenge
Demonstrate that spatial statistics can reproduce the nonlinear order parameter that I found to be highly correlated with device performance. Identify which naive dimensionality reduction algorithms are best at finding it.

#### Potential Difficulties
Math.
