# AI Tennis Analysis

## Introduction
This is my self-learning project that analyzes Tennis players in a video to measure their speed, ball shot speed and number of shots. This project will detect players and the tennis ball using YOLO.

## Models Used
+ YOLO v8 for player detection
+ Online Tuned YOLO for tennis ball detection
+ Court Key point extraction

* Trained YOLOV5 model & Trained tennis court key point model: https://drive.google.com/drive/folders/1kwHsv54Avk-wvM__0T_IHFh6XqMAettF?usp=sharing

## Training
* Tennis ball detetcor with YOLO: training/tennis_ball_detector_training.ipynb
* Tennis court keypoint with Pytorch: training/tennis_court_keypoints_training.ipynb

## Some Requirements
* python3.8
* ultralytics
* pytroch
* pandas
* numpy 
* opencv

# Inspired from Code In a Jiffy
