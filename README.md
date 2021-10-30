
# Pose Detection by using Mediapipe
Run real-time pose estimation in the browser using Mediapipe Library can be used to estimate either a single pose or multiple poses, meaning there is a version of the algorithm that can detect only one person in an image/video and one version that can detect multiple persons in an image/video.

This is a Pure Mediapipe Library implementation of PoseNet. Thank you Google for your flexible and intuitive APIs.


## Technologies

You can use this as standalone mediapipe bundle like this:

  Mediapipe
  Opencv-python
  flask 
  time

## Installation

You have to install the required packages, you can do it

via pip `pip install -r requirements.txt`

or via conda `conda env create -f environment.yml`

Once you installed all the required packages you can type in the command line from the root folder:

  `python app.py`

and click on the link that the you will see on the prompt.

## Usage

Either a single pose our multiple poses can be estimated from an image. Each methodology has its own algorithm and set of parameters.

| Id             | Part                                                                |
| ----------------- | ------------------------------------------------------------------ |
| 0 | nose |
| 1 | leftEye |
| 2 | rightEye |
| 3 | leftEar |
| 4 | rightEar |
| 5 | leftShoulder |
| 6 | rightShoulder |
| 7 | leftElbow |
| 8 | rightElbow |
| 9 | leftWrist |
| 10 | rightWrist |
| 11 | leftHip |
| 12 | rightHip |
| 13 | leftKnee |
| 14 | rightKnee |
| 15 | leftAnkle |
| 16 | rightAnkle |

## Developing the Model for demos
Details for how to run the model are included in the folder.
if anything worng please correct me.

## Credits
Credits for this code go to Google




    