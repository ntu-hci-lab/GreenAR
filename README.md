# GreenAR: Natural Soundscape Restoration with Personal Audio AR

[![Paper](https://img.shields.io/badge/CHI'26-Paper-red)](https://doi.org/10.1145/3772318.3791961)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

[Yu Chen](https://github.com/chenyutpe), [Yu-Cheng Chang](https://github.com/Malik705017), [Yu Lun Hsu](https://github.com/YuLunHsu0912), [Mike Y. Chen](https://mikechen.com/)

This repository contains the open-source framework for the CHI '26 paper: **"Reacquainting with Everyday Urban Nature: Exploring Natural Soundscape Restoration with Personal Audio AR"**.

## Overview

**GreenAR** is a ubiquitous, location-aware Audio AR system that restores natural soundscapes by composing spatial, visually-congruent biophony (bird and insect sounds) based on **OpenStreetMap** greenery data. 

The system integrates head-tracked spatial audio via AirPods, allowing users to experience a plausible, ecologically informed soundscape integrated into their daily urban environment.

## Important Note on Assets

This repository provides the **technical framework** and system logic. Due to licensing constraints:

- **Geo-database assets** (visual, audio, and field guide text) are **NOT included**.
- The project contains **placeholder objects** where these assets should be integrated.

## Getting Started

### Environment

- **Unity Version:** `2022.3.32f1`
- **Target Platform:** iOS

### Installation

- Import the provided `.unitypackage`

## Citation

If you find this project helpful, please cite our paper:

```bibtex
@inproceedings{chen2026reacquainting,
  author = {Chen, Yu and Chang, Yu-Cheng and Hsu, Yu Lun and Chen, Mike Y.},
  title = {Reacquainting with Everyday Urban Nature: Exploring Natural Soundscape Restoration with Personal Audio AR},
  year = {2026},
  publisher = {Association for Computing Machinery},
  address = {New York, NY, USA},
  url = {https://doi.org/10.1145/3772318.3791961},
  doi = {10.1145/3772318.3791961},
  booktitle = {Proceedings of the 2026 CHI Conference on Human Factors in Computing Systems},
  series = {CHI '26}
}
```

## License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.
