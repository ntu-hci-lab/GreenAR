# GreenAR: Natural Soundscape Restoration with Personal Audio AR

[![CHI'26 Best Paper](https://img.shields.io/badge/CHI'26-🏆%20Best%20Paper-80aa80)](https://doi.org/10.1145/3772318.3791961)
[![License: MIT](https://img.shields.io/badge/License-MIT-7faeb3)](https://opensource.org/licenses/MIT)

[Yu Chen](https://github.com/chenyutpe), [Yu-Cheng Chang](https://github.com/Malik705017), [Yu Lun Hsu](https://github.com/YuLunHsu0912), [Mike Y. Chen](https://mikechen.com/)

This repository contains the open-source framework for the **CHI '26 Best Paper 🏆: "Reacquainting with Everyday Urban Nature: Exploring Natural Soundscape Restoration with Personal Audio AR"**.

https://github.com/user-attachments/assets/8842ccc4-8131-4c30-ab37-ad836bf894eb

> 🚧 **Notice: Active Refactoring & Early Access** 🚧
>
> We are currently in the process of refactoring this repository to provide a seamless, out-of-the-box developer experience. The current version lacks some integration files and detailed setup instructions necessary to run the project perfectly. 
>
> **What's Next:** We are preparing **example files and placeholder assets** to make testing the system much more convenient in the near future.
>
> **Want to try it out or collaborate?** 
> If you are interested in testing GreenAR, deploying it for your own project, or just want to chat about the system, please feel free to reach out directly to the first author: **[chenyutpe@gmail.com](mailto:chenyutpe@gmail.com)**. We would be happy to guide you through the current setup or discuss future collaborations!



## Overview

**GreenAR** is a ubiquitous, location-aware Audio AR system that restores natural soundscapes by composing spatial, visually-congruent biophony (bird and insect sounds) based on **OpenStreetMap** greenery data. 

The system integrates head-tracked spatial audio, allowing users to experience a plausible, ecologically informed soundscape integrated into their daily urban environment.

## Hardware Requirements

To run the GreenAR iOS app, the following hardware is required:

- **Device:** iPhone (iOS)
- **Earphones (Recommended):** AirPods Pro (all generations), AirPods Max (all generations), or AirPods (3rd generation and newer). These devices support real-time **head-tracking**, which provides the optimal immersive spatial audio experience.
- **Earphones (Fallback Mode):** Standard earphones/headphones are also supported! If head-tracking hardware is not detected, GreenAR gracefully degrades to a fallback mode that uses the **iPhone's device orientation** to position the spatial audio.

## Important Note on Assets

This repository provides the **technical framework** and system logic. Due to licensing concerns:

- **Geo-database assets** (visual, audio, and field guide text) are **NOT included**.
- The project currently contains **placeholder objects** where these assets should be integrated.

## Getting Started

### Environment & Dependencies

- **Unity Version:** `2022.3.32f1`
- **Target Platform:** iOS
- **Core SDKs:** FMOD (with Resonance Audio plugin), Mapbox, and [HeadphoneMotion](https://github.com/anastasiadevana/HeadphoneMotion)

### Installation

- Import the provided `.unitypackage` into your Unity project. *(Detailed setup documentation is currently being written).*

## Acknowledgments

A special thanks to [Anastasiia Devana](https://github.com/anastasiadevana) for the open-source [HeadphoneMotion](https://github.com/anastasiadevana/HeadphoneMotion) plugin, which was instrumental in enabling the AirPods real-time head-tracking integration within Unity for this project.

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