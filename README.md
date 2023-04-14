# Gas-Meter-Tracker

This project was the final project for my Large-Scale Machine Learning class. 

My professor was interested in tracking the gas usage of his apartment complex. He set up a camera to take photos every fifteen seconds of his gas meter. The goal of this project was to create a model that could read the digits of this gas meter from the photos.

Here is what the readings looked like

![](https://i.imgur.com/FhZYBqO.png)

The project was split into three components:
1. A convolutional network trained on complete digits
2. A convolutional network trained on isolated digits
3. A convolutional network trained on perturbed digits

I have attached my final submission. While it does not completely reflect the many hours I poured into experimentation (most notably the RNN models I developed), it does outline some of my thought process and showcase my comfort with several types of neural networks.

Additionally, the entire course was taught in PyTorch. For this project I chose to learn Keras (a TensorFlow interface) entirely on my own because I was interested in how the interface could lead to much faster development and iteration and in turn higher quality models. 

I'm incredibly proud of this decision as Keras turned out to be an invaluable tool for agile development that I continue to use to this day for building sophisticated neural networks.
