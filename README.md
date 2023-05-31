# Personalized ResNet18 Image Classifier model for PyTorch Framework

### Run driver.py to train the model for a user-defined number of epochs.
```python driver.py```
### Run inference.py to run inference for images added in the inference_images/images/ directory.
```python inference.py -img_path 'enter inference images path' -model_path 'enter the saved model's path'```
### In our case:
img_path = './inference_images/images/'
model_path = './cifar_net.pth' (generated after running driver.py)
### The model is pre-trained using ImageNet dataset, hence can be used to classify the following 10 classes:

- airplane
- automobile
- bird
- cat
- deer
- dog
- frog
- horse
- ship
- truck
