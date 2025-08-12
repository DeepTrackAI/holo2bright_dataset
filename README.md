# Holo2Bright Dataset (holo2bright_dataset)

## Overview

This DeepTrackAI repository provides a copy of the **Holo2Bright** dataset, consisting of unpaired holographic and bright-field microscopy images of marine microplankton.  
The dataset originates from [Bachimanchi et al., eLife, 2022] (https://doi.org/10.7554/eLife.79760), where it was used to train and evaluate deep learning models for reconstructing bright-field images from holograms.

### Summary
- **Number of images**:  
  - Training set: 4,500 holographic + 880 bright-field images  
  - Test set: 4,500 holographic + 244 bright-field images  
- **Image size**: 256 × 256 pixels  
- **Format**: 8-bit grayscale PNG  

---

## Original Source

- **Title**: Microplankton life histories revealed by holographic microscopy and deep learning
- **Authors**: Harshith Bachimanchi, Benjamin Midtvedt, Daniel Midtvedt, Erik Selander, Giovanni Volpe  
- **Journal**: eLife, 11:e79760 (2022)  
- **DOI**: [10.7554/eLife.79760](https://doi.org/10.7554/eLife.79760)  

If you use this dataset in your research, you must follow the licensing requirements and properly attribute the original authors.

---

## Dataset Structure

```bash
/holo2bright_dataset
├── train/
│   ├── holograms/          # 4,500 holographic images (256×256 PNG)
│   └── brightfield/        # 880 bright-field images (256×256 PNG)
└── test/
    ├── holograms/          # 4,500 holographic images (256×256 PNG)
    └── brightfield/        # 244 bright-field images (256×256 PNG)
```

---

## How to Access the Data

### Clone the Repository
```bash
git clone https://github.com/DeepTrackAI/holo2bright_dataset
cd holo2bright_dataset
```

---

## Attribution

### Cite the paper:
Bachimanchi H, Midtvedt B, Midtvedt D, Selander E, Volpe G. *Microplankton life histories revealed by holographic microscopy and deep learning.* eLife 11:e79760 (2022). [https://doi.org/10.7554/eLife.79760](https://doi.org/10.7554/eLife.79760)

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

This dataset is shared under the **Creative Commons Attribution 4.0 International** License, following the original licensing terms.
