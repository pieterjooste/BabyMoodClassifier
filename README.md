[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/pieterjooste/BabyMoodClassifier.git/Git branch, tag or commit?filepath=%2Fvoila%2Frender%2FBabyClassifier_v1.ipynb)

#BabyClassifier

Image classifier

Lesson 2 Fastai Course: Image classifier and deploy app on the web.

Based on Bear classifier.

Uploaded 45 images of happy and sad babies (50:50) less than 2 years from a Google Search.

Copied images to a total of 90 images.

Data split by RandomSplitter (80:20) in training and validation set.

Model trained with Resnet 34 on P5000 with 8 CPUs with learning rate of 0.01.

No improvement after 10 epochs.

Reached accuracy of 89%.

Forum posting on Fastai by Vikrant Behal May 2020 made deployment of model on an app possible. (most difficult part of assignment)

#Using App

Launch Binder using icon above.

Upload photo of a single baby less than 2 years.

Photo will automatically be classified as happy or sad with a probability.

If wrong: Please send photo to me at pieter.jooste.jp@gmail.com

#Future

I am a retired pediatrician. I want to build a model that can triage babies.

Using a photo and measurements(temperature, pulse, respiratory rate, oxygen saturation) it should classify babies as healthy, ill or acutely ill.
