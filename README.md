[//]: # (Image References)

[image1]: ./images/sample_dog_output.png "Sample Output"
[image2]: ./images/vgg16_model.png "VGG-16 Model Layers"
[image3]: ./images/vgg16_model_draw.png "VGG16 Model Figure"

# Udacity Deep Learning Nanodegree Program - Project: Dog-Breed Classifier

This project builds a pipeline that can be used within a web or mobile app to
process real-world, user-supplied images.  Given an image of a dog, the
algorithm will identify an estimate of the canine’s breed. If supplied an image
of a human, the code will identify the resembling dog breed.  

![Sample Output][image1]

## Setup Instructions

Clone the repository and navigate to the downloaded folder:

```bash
git clone https://github.com/thom/dog-breed-classifier.git
cd dog-breed-classifier
```

Download the [dog dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip). Unzip the folder and place it in the repo, at location `dogImages/`. The `dogImages/` folder should contain 133 folders, each corresponding to a different dog breed.

Download the [human dataset](http://vis-www.cs.umass.edu/lfw/lfw.tgz). Unzip the folder and place it in the repo, at location `lfw/`.

Make sure you have already installed the necessary Python packages:

```bash
conda install pytorch torchvision -c pytorch
```

Open a terminal window and navigate to the project folder. Open the notebook and follow the instructions:

```bash
jupyter lab dog_app.ipynb
```

## Requirements

Graded according to the [Project Rubric](https://review.udacity.com/#!/rubrics/2259/view).

## License

- **[MIT license](http://opensource.org/licenses/mit-license.php)**
- Copyright 2021 © [Thomas Weibel](https://github.com/thom).