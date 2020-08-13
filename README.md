This repo documents our research in the most recent mocap approaches. These 2 approaches are the most successful
**1: PIFuHD** 
  We changed the code from this paper https://ai.facebook.com/research/publications/pifuhd-multi-level-pixel-aligned-implicit-function-for-high-resolution-3d-human-digitization/
  which constructs 3d models with fine details including occluded parts, to accomodate video input.
    * https://colab.research.google.com/drive/1pSU9msr7nXHpllaCssvBFa5_tRl3oWTP?usp=sharing#scrollTo=z7pHnWccixto
**2: OpenPose Multiperson (found in this repo in the notebook titled Test.ipynb)**
  The code belongs to the blog https://www.learnopencv.com/multi-person-pose-estimation-in-opencv-using-openpose and was modified in Test.ipynb to accomodate web cam multiperson pose detection (instead of image-only pose detection)

  ***A.Requirements :*** 
  1. OpenCV > 3.4.1
  2. Matplotlib for Notebook
  3. RUN getModels.sh from command line Or Download caffe model from http://posefs1.perception.cs.cmu.edu/Users/ZheCao/pose_iter_440000.caffemodel and put it in pose/coco folder
**
**3: lightweight-human-pose-estimation**
  We also tried the code from this repo https://github.com/Daniil-Osokin/lightweight-human-pose-estimation-3d-demo.pytorch and it was ran successfully. 

