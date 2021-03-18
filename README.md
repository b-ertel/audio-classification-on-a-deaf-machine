# Audio classification on a deaf machine
A novel method for transforming audio clips into melspectrograms for
classification. The classification algorithm we used is a convolutional network
similar to the VGG-Net. The results seem promising with accuracy up to 80 % and
an average of 74.1 % using cross validation. 

## In this repository:
- [audio-images](https://github.com/b-ertel/audio-classification-on-a-deaf-machine/tree/main/audio_images) the transformed dataset
- [Audio-classification-deaf-machine.pdf](https://github.com/b-ertel/audio-classification-on-a-deaf-machine/blob/main/Audio-classification-deaf-machine.pdf) write-up describing the theory behind, the method, discussing the results and looking ahead
- [Audio_classification_deaf_machine.ipynb](https://github.com/b-ertel/audio-classification-on-a-deaf-machine/blob/main/Audio_classification_deaf_machine.ipynb) jupyter notebook implementing and training the network
- [data_processing.ipynb](https://github.com/b-ertel/audio-classification-on-a-deaf-machine/blob/main/data_processing.ipynb) jupyter notebook implementing the transformation from the [original dataset](https://urbansounddataset.weebly.com/urbansound8k.html) to the [transformed dataset](https://github.com/b-ertel/audio-classification-on-a-deaf-machine/tree/main/audio_images)
