# Human eye iris and pupil segmentation using infrared camera snapshots

At the present time, problems related to the automation of medical technology are the urgent. Particularly human physiological 
parameters monitoring and analysis systems are under the great attention nowadays.
Usually, special types of sensors such as an infrared camera are used for source image acquisition in such systems. Among a 
variety of physiological parameters features, there are related to human eye parameters such as iris, pupil have the great importance.

This repository contatains a dataset used for a research on human pupil and iris segmentation problem using snapshots captured by 
infrared camera. In our work we propose custom architecture and novel special loss for training human eye segmentation neural network models. We also 
present comparative analysis of segmentation technique approaches applied to the dataset. 
Also our model outperforms other consider approaches on the proposed dataset and demonstrate state-of-the-art result.

```
citation stub
```

We collected and labelled an **InP** dataset, which we have prepared together with NPP VIDEOMIX. 
The dataset is represented with annotated pairs of the following form: an image of a human eye captured by an infrared camera, 
and a binary segmentation mask corresponding to a particular object (pupil and iris). The sample from the dataset is below:
