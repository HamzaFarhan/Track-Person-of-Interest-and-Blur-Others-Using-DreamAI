# Track-Person-of-Interest-and-Blur-Others-Using-DreamAI
Using pre-trained face detection and object detection models to detect and blur out people who are not the person of interest (PoI).

DreamAI is an under development deep learning library written in Pytorch and inspired by FastAI. This notebook is not a tutorial on DreamAI, it is just an example of how it can be used for video urveillance. Stay tuned for a detailed overview/tutorial of DreamAI as well as other examples.

You can find the library here: https://github.com/fzaidi2014/dreamai

Any kind of feedback is much appreciated.

We will use a face detection model combined with an object detection model both already trained using DreamAI.

The user will select a PoI in a video and then that person will be tracked and every other face will be blurred out.

# Usage

Download or clone DreamAI from the link provided above.

Download or clone this repository, make sure you set up the paths correctly, and the notebook should run smoothly.
