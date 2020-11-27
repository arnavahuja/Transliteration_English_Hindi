# Transliteration_English_Hindi
This is a self project undertaken as a part of my learning experiences with deep learning

## Introduction
Transliteration is a type of conversion of a text from one script to another that involves swapping letters. This has a wide variety of real life application like google translate.

## Encoder Decoder Models
An encoder is a network (FC, CNN, RNN, etc) that takes the input, and output a feature map/vector/tensor. These feature vector hold the information, the features, that represents the input. The decoder is again a network (usually the same network structure as encoder but in opposite orientation) that takes the feature vector from the encoder, and gives the best closest match to the actual input or intended output.

The encoder and decoder both are Recurrent Neural Networks. Attention mechanism has also been applied for better accuracy.
<p align="center"> <img src="https://cdn-images-1.medium.com/fit/t/1600/480/1*MQRKHT7pr_vF4V7A82TUhg.png" width=700> </p>

