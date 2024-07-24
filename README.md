# image-caption-generation
This project focuses on generating captions for images using deep learning techniques. It involves training a neural network on a dataset of images and their corresponding captions to create a model capable of predicting captions for new images.
**VGG16**: A pre-trained Convolutional Neural Network (CNN) used for extracting features from images. VGG16 is known for its depth and the simplicity of using only 3x3 convolutional layers stacked on top of each other in increasing depth.
- **LSTM (Long Short-Term Memory)**: A type of Recurrent Neural Network (RNN) utilized for generating captions. LSTMs are effective for sequence prediction problems due to their ability to learn long-term dependencies.
- **Encoder-Decoder Architecture**: Combines the CNN (VGG16) for encoding images into a fixed representation and the RNN (LSTM) for decoding this representation into a sequence of words (captions).

