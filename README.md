# PalmNavigator

## Intro

This project is inspired by Disney Research's [Catching a Real Ball in Virtual Reality](https://www.disneyresearch.com/publication/catching-a-real-ball-in-virtual-reality/). I was impressed with the concept of computer guiding individual human's body-parts for improved human's performance in particular tasks. This is like Google Maps but for the palm!

The goal is to replicate the experiment in a cheaper and more general fashion.

## Components

Main hardware components will be:

- one or two Microsoft Kinect 2 sensors;
- a PC;
- Google Daydream compatible phone and headset;
- possibly, a passive marker.

A passive marker may be necessary to determine how Kinect's and headset's coordinate systems relate.

Main software components will be:

- probabilistic model to determine the position of the ball and the palm based on Kinect's output;
- probabilistic model to predict the ball's trajectory;
- probabilistic model to determine headset's position relative to Kinect(s);
- VR scene rendering the palm and directions for the palm.

Data for training probabilistic models will be quicky obtained with the help of a separate project I am working on: [Using VR for ground-truth annotation](http://blog.pletnikov.com/post/161851918870/using-vr-for-ground-truth-annotation)
