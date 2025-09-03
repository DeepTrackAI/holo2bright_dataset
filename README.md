# Holo2Bright Dataset (holo2bright_dataset)

## Overview

This DeepTrackAI repository provides a copy of the **Holo2Bright** dataset, consisting of unpaired holographic and bright-field microscopy images of marine microplankton.  
The dataset originates from [Bachimanchi et al., eLife, 2022] (https://doi.org/10.7554/eLife.79760), where it was used to train and evaluate deep learning models for reconstructing bright-field images from holograms.

### Summary
- **Number of images**:  
  - Training set: 4,500 holographic + 880 bright-field images  
  - Test set: 4,500 holographic + 244 bright-field images
  - Test video 100 holographic + 100 bright-field images
- **Image size**: 256 × 256 pixels  
- **Image format**: 8-bit grayscale PNG  

---

## Original Source

- **Title**: Holo2Bright dataset  
- **Authors**: Harshith Bachimanchi, Benjamin Midtvedt, Daniel Midtvedt, Erik Selander, Giovanni Volpe  
- **Source**: This repository  
- **Reference article**: Bachimanchi S. et al. *eLife* 11:e79760 (2022). [DOI: 10.7554/eLife.79760](https://doi.org/10.7554/eLife.79760)  
- **License**: [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/)

If you use this dataset in your research, please follow the licensing requirements and properly attribute the original authors.

---

## Dataset Structure

```bash
/holo2bright_dataset
└── holo2bright/
    └── train/                # Training set (static images)
        ├── holography/       # Holographic images
        │   ├── 00000.png
        │   ├── 00001.png
        │   └── ...
        ├── brightfield/      # Bright-field images
        │   ├── 00000.png
        │   ├── 00001.png
        │   └── ...
        ├── test/             # Test set (static images)
        │   ├── holography/   # Holographic images
        │   │   ├── 00000.png
        │   │   ├── 00001.png
        │   │   └── ...
        │   └── brightfield/  # Bright-field images
        │       ├── 00000.png
        │       ├── 00001.png
        │       └── ...
        └── test_videos/      # Test set (video sequences exported frame by frame)
            ├── holography/   # Holographic frames
            │   ├── 00000.png
            │   ├── 00001.png
            │   └── ...
            └── brightfield/  # Bright-field frames
                ├── 00000.png
                ├── 00001.png
                └── ...       
```

Each filename is a sequential numerical identifier. The `test_videos` folder contains frame-by-frame exports of dynamic sequences, in contrast to the static snapshots in `test/`.

---

## How to Access the Data

### Clone the Repository
```bash
git clone https://github.com/DeepTrackAI/holo2bright_dataset
cd holo2bright_dataset
```

---

## Attribution

If you use this dataset, please cite both the Holo2Bright dataset repository and the reference article.

### Cite this repository:
Bachimanchi H, Midtvedt B, Midtvedt D, Selander E, Volpe G. *Holo2Bright Dataset* GitHub (2025). [GitHub](https://github.com/DeepTrackAI/holo2bright_datase)

```bibtex
@misc{bachimanchi2025holo2bright,
  author={Bachimanchi, Harshith and Midtvedt, Benjamin and Midtvedt, Daniel and Selander, Erik and Volpe, Giovanni},
  title        = {Holo2Bright Dataset},
  year         = {2025},
  howpublished = {\url{https://github.com/DeepTrackAI/holo2bright_dataset}}
}
```

### Cite the reference article:
Bachimanchi H, Midtvedt B, Midtvedt D, Selander E, Volpe G. *Microplankton life histories revealed by holographic microscopy and deep learning.* eLife 11:e79760 (2022). [DOI: 10.7554/eLife.79760](https://doi.org/10.7554/eLife.79760)

```bibtex
@article{bachimanchi2022microplankton,
  title={Microplankton life histories revealed by holographic microscopy and deep learning},
  author={Bachimanchi, Harshith and Midtvedt, Benjamin and Midtvedt, Daniel and Selander, Erik and Volpe, Giovanni},
  journal={eLife},
  volume={11},
  pages={e79760},
  year={2022},
  publisher={eLife Sciences Publications Limited},
  doi={10.7554/eLife.79760}
}
```

---

## License

This dataset is shared under the [Creative Commons Attribution 4.0 International (CC BY 4.0) License](https://creativecommons.org/licenses/by/4.0/).
