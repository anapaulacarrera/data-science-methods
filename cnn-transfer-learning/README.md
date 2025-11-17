# Transfer Learning CNN Image Classification 
## Convolutional Neural Network Using Transfer Learning 
This project applies Convolutional Neural Networks (CNNs) with transfer learning to classify images using a pre-trained MobileNetV2 model from TensorFLow Hub. Custom Dense layers were added on top of the frozen base, and the model was trained using the Monkey Species Dataset from Kaggle, which conatins ~10,000 labeled images across 10 monkey species.

The dataset was loaded from a public URL, processed using ImageDataGenerator, and automatically split into training and validation sets. 

### Key Skills 
- Transfer learning with MobileNetV2
- Building and fine-tuning CNN classifier heads
- Image preprocessing with ImageDataGenerator
- Training/evaluating CNNs using accuracy & loss curves
- Making predictions and logging tuning results 
