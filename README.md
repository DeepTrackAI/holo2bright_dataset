# Holo2Bright dataset

Welcome to the GitHub page of DeepTrackAI's Holo2Bright dataset. The Holo2Bright dataset is a collection of unpaired images of planktons belonging to two different microscopic modalities namely holographic microscopy and bright-field microscopy. The dataset is used for training and evaluating CycleGAN models for unpaired image-to-image translation.

## Description

The Holo2Bright dataset consists of images of microplankton imaged under two different microscopic systems, namely holographic microscopy and brightfield microscopy.

The dataset consists of three folders, namely:

- `train` consisting of 4500 holographic images and 880 brightfield images under the subfolders `holography`and `brightfield` respectively.
- `test` consisting of 4500 holographic images and 244 brightfield images under the subfolders `holography`and `brightfield` respectively.

Holographic images are grayscale images, and brightfield images are RGB images. The images are of size 256x256 pixels.

Since the images are unpaired, the images in the `holography` and `brightfield` subfolders are not aligned.

## Usage

To use the Holo2Bright dataset in your project,

1. Clone the repository to your local machine.
2. Import the dataset into your machine learning framework of choice.
3. Train or evaluate your models using the dataset.

### Download via command line

To clone the repository and access the Holo2Bright dataset:

```
git clone https://github.com/DeepTrackAI/holo2bright_dataset.git
cd holo2bright_dataset
```

## Acknowledgements

The Holo2Bright dataset was originally created by Harshith Bachimanchi, Erik Selander & Giovanni Volpe at the Soft Matter Lab, University of Gothenburg, Sweden.

## License

The Holo2Bright dataset is made available under the [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).

## Contributing

If you find any issues with the dataset or have suggestions for improvements, please open an issue or submit a pull request.
