# EEG Model Collection
This repo will contain some of Neural network models which design for EEG specific task. All of model in here are implemented on **pytorch** since my lab (AIT Brainlab) prefer this framework and I beleive that there are many implementation on TensorFlow or Keras already.

# Getting start
## Requirements
These codes require these packages below 
```
torch
numpy
```

## Download the code
1. Change to your project directory.
2. Clone this repo using command 
    ```bash
     git clone https://github.com/nopphonyel/EEGModelCollection.git
     ```

## Import code
To import the model, simply add the code below on the top of your python file.

```python
from EEGModelCollection import <Your Component>
```
For example, to import EEGNet component and EEGChannelNetEncoder
```python
from EEGModelCollection import EEGNet
from EEGModelCollection import EEGChannelNetEncoder
``` 

# Model explaination
In this section, I will give the information about all models in the collection. The informations include architecture, arguments and how to use it.
- [EEGNet](docs/EEGNet/EEGNet.md)

