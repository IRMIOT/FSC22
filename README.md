
# FSC22 - A dataset for forest sound classification

Forest-specific sound dataset under 27 classes


## Badges

Add badges from somewhere like: [shields.io](https://shields.io/)

[![CC0 1.0 Universal](https://img.shields.io/badge/License-MIT-green.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
[![Download](https://camo.githubusercontent.com/ccd63ba26a688c72062ed82460b91e731d266512395d9f82478ecb07a63c7123/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f646f776e6c6f61642d2e7a69702d6666363962342e737667)](https://github.com/IRMIOT/FSC22/tree/main/Audios)

## Demo

Insert gif or link to demo

![Alt Text](https://res.cloudinary.com/dduse1ior/image/upload/v1663901034/ezgif.com-gif-maker_ab6i1r.gif)


## About dataset

Forest environmental sound classification is one use case of ESC which has been widely experimenting to identify illegal activities inside a forest. With the unavailability of public datasets specific to forest sounds, there is a requirement for a benchmark forest environment sound dataset. With this motivation, the FSC22 was created as a public benchmark dataset, using the audio samples collected from FreeSound org.

This dataset includes 2025 labeled sound clips of 5s long. All the audio samples are distributed between six major parent-level classes; Mechanical sounds, Animal sounds, Environmental Sounds, Vehicle Sounds, Forest Threat Sounds, and Human Sounds. Further, each class is divided into subclasses that capture specific sounds which fall under the main category. Overall the dataset taxonomy consists of 34 classes as shown below. For the first phase of the dataset creation, 75 audio samples for every 27 classes were collected. 

![App Screenshot](https://res.cloudinary.com/dduse1ior/image/upload/v1663900199/Taxonomy_zr6axd.jpg)

We expect that this dataset will help research communities with their research work governing Forest Acoustic monitoring and classification domain.

## Download

The dataset can be downloaded as a single .zip file (~600 MB):

[Download FSC22 Dataset](https://github.com/IRMIOT/FSC22/tree/main/Audios)
## Repository content

- [Audios](https://github.com/IRMIOT/FSC22/tree/main/Audios)
The Dataset contains 27 classes, each containing 75 audios related to the given class name.
In the folder structure of the FSC22 dataset, users can navigate to the Audios folder to access the audio files.

The name of the audio files are derived as follows,
    UniqueClassIndex_UniqueAudioID.wav eg: 1_10101.wav

To identify the audio level details, users are expected to use either,
    - [Metadata V1.0 FSC22.csv](https://github.com/IRMIOT/FSC22/blob/main/Metadata/Metadata%20V1.0%20FSC22.csv)
    - [Metadata V1.0 FSC22_.xlsx](https://github.com/IRMIOT/FSC22/blob/main/Metadata/Metadata%20V1.0%20FSC22_.xlsx)
Located inside the Metadata Folder.

For each audio file, the Metadata file provides: 
    Source File Name - ID of the original audio sample, used to extract the corresponding audio.
    Dataset File Name - ID of the audio, in the context of FSC22
    Class ID - Class Identification index (An integer from the range 1 to 27)
    Class Name - Class Name which the audio is classified in.

 


## License

The dataset is available under the terms of the [CC0 1.0 Universal license](https://creativecommons.org/publicdomain/zero/1.0/).

A smaller subset (clips tagged as FSC22) is distributed under CC BY (Attribution).

Attributions for each clip are available in the [LICENSE file](https://github.com/IRMIOT/FSC22/blob/main/LICENSE).

## Authors

- [@Roshinie Jayasundara](https://www.github.com/octokatherine)
- [@Meelan Bandara](https://github.com/Meelan-98)
- [@Isuru Ariyarathne](https://github.com/IsuruAriyarathne)


## Acknowledgement

- [@S.D. Rajapaksha](#)
- [@D.P.C.L.Dombawala](#)
- [@H.B.K.S. Siriwardana](#)