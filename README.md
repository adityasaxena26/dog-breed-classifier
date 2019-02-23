# Deep Learning Nanodegree
## Convolutional Neural Networks
## CNN Project: Dog breed classifier

## Project Overview
In this project, you will build a pipeline that can be used within a web or mobile app to process real-world, user-supplied images. Given an image of a dog, the algorithm will identify an estimate of the canine’s breed. If supplied an image of a human, the code will identify the resembling dog breed.

![sample dog output](images/sample_dog_output.png)

## Project Instructions

### Instructions
1. Clone the repository and navigate to the downloaded folder.
  ```
  git clone https://github.com/udacity/dog-project.git
  cd dog-project
  ```
2. Download the [dog dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip). Unzip the folder and place it in the repo, at location path/to/dog-project/dogImages.

3. Download the [human dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/lfw.zip). Unzip the folder and place it in the repo, at location path/to/dog-project/lfw. If you are using a Windows machine, it is recommended to use [7zip](http://www.7-zip.org/) to extract the folder.

4. Download the [VGG-16 bottleneck features](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/DogVGG16Data.npz) for the dog dataset. Place it in the repo, at location path/to/dog-project/bottleneck_features.

5. (Optional) If you plan to install TensorFlow with GPU support on your local machine, follow [the guide](https://www.tensorflow.org/install/) to install the necessary NVIDIA software on your system. If you are using an EC2 GPU instance, you can skip this step.

6. (Optional) If you are running the project on your local machine (and not using AWS), create (and activate) a new environment.

  * Linux (to install with GPU support, change ```requirements/dog-linux.yml to requirements/dog-linux-gpu.yml```):

  ```conda env create -f requirements/dog-linux.yml```

  ```source activate dog-project```

  * NOTE: Some Mac users may need to install a different version of OpenCV

  ```conda install --channel https://conda.anaconda.org/menpo opencv3```
