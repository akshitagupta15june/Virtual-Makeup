# Virtual-Makeup

## Inspiration

Virtual Makeup is a smart beauty camera app feature that allows users to try on makeup, hair colors, and accessories via augmented reality. It works with neural networks trained to detect and modify the right part of the face e.g. lips or hair and face tracking technology to provide real-time experience.

## What it does

You need to determine what features it should include and how you can scale them in the future. Here is a shortlist of the most significant functionality considered while building a beauty AR app:

Real-time makeover

Face beautification

Virtual hair color try-on

Facial feature modification e.g. slim down cheeks

Photo/video editing

Face filters and AR effects

Beauty community

Social network integration

## How we built it

Requirements
numpy
scikit_image
opencv_python
Pillow
skimage
dlib

Provide two images in the Images folder

## What we learned

Features:

Detect and auto-align faces in images 

Generate corresponding features points between the two images using Dlib's Facial Landmark Detection

Warp the two input images towards the intermediate shape, perform cross-dissolve and obtain intermediate images each frame

## What's next for Virtual-Makeup

We will try to make it more efficient.
