# Age estimation from face images using regression methods
> September-December 2018, ENSIIE, Evry, France

The UTKFace dataset is a large scale face dataset. It contains over 20 000 face images. The images cover large variation in pose, facial expression, illumination, occlusion, resolution, etc.
The information on the JPG images provided are :
- age : an interger between 0 and 116
- gender : 0 (male) or 1 (female)
- race : an integer from 0 to 4, denoting White, Black, Asian, Indian, and Others (like Hispanic, Latino,
Middle Eastern)
- date & time: is in the format of yyyymmddHHMMSSFFF, showing the date and time an image was collected
to UTKFace

# The general nature of the problem

The aim of the problem is to estimate the age of a face from an image. We will construct a model from the variables provided. The target variable is age. The co-variable are gender, race and we also will include information about the images such as grayscale or RGB color intensity per pixel.
In the problem, we will use about 10 000 face images.


# Authors
+ Project realized during the course of Regularized Regressions, 3rd semester at ENSIIE in 2018.

+ **Kevin XU** - *Applied Mathematics Student ENSIIE* - [kevinxu-git](https://github.com/kevinxu-git)
+ **Ziheng LI** - *Applied Mathematics Student ENSIIE* - [zihengli](https://github.com/zihengli)
