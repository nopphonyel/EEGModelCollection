# EEGNet
This model implementation is following the paper : EEGNet: A Compact Convolutional Neural Network for EEG-based Brain-Computer Interfaces

- link to the papaer: https://arxiv.org/abs/1611.08024
- link to the original code : https://github.com/vlawhern/arl-eegmodels

| Argument | Description |
| - | - |
| ```in_channel``` | The number of EEG Channel (Or number of electrodes on your BCI device).|
| ```samples``` | The number of EEG samples (data point) of EEG input. |
| ```kern_len``` | **[Hyper Parameter]** The size of the 1D kernel in first layer (From the paper, they recommend to use ```size = sampling_rate//2``` in order to capture information at 2Hz).
| ```F1``` | **[Hyper Parameter]** The number of temporal features. |
| ```F2``` | **[Hyper Parameter]** The number of pointwise filters. |
| ```D``` | **[Hyper Parameter]** The depth multipiler. |
| ```nb_classes``` | **[Hyper Parameter]** The number of output class. |
| ```dropout_type``` | ```{'2D','classics'}``` **[Hyper Parameter]** **[Default='2D']** Type of dropout layers. Currently I'm not sure the differences.
| ```dropout_rate``` | **[Hyper Parameter]** **[Default=0.5]** The p value of dropout
| ```norm_rate``` | **[Hyper Parameter]** **[Default=0.25]**