<div align="center">
<b><font size="5">InternLandMark</font></b>
</div>

![GitHub User's stars](https://img.shields.io/github/stars/InternLandMark?affiliations=OWNER%2CCOLLABORATOR)

Welcome to the InternLandMark homepage. InternLandMark is mainly developed by Shanghai AI Laboratory. We welcome contributions to our project in different forms.

## Release
- LandMark 1.0

  We propose the project LandMark, the groundbreaking large-scale 3D real-world city scene modeling and rendering system. The project is built upon [GridNeRF](https://city-super.github.io/gridnerf/) (CVPR23). Please refer to the [document page](https://internlandmark.github.io/LandMark_Documentation/) for more details.

- LandMark 2.0:

  We build a large-scale, comprehensive, and high-quality synthetic dataset [MatrixCity](https://city-super.github.io/matrixcity/) (ICCV 2023) for city-scale neural rendering researches.

  We propose the [Scaffold-GS](https://city-super.github.io/scaffold-gs) (CVPR24, Highlight), which combines the high-performance rendering efficiency of 3D Gaussian Splatting with the flexibility and high quality of various classic NeRF representations.

  Inspired by the Level-of-Detail (LOD) techniques, we introduce [Octree-GS](https://city-super.github.io/octree-gs), featuring an LOD-structured 3D Gaussian approach supporting level-of-detail decomposition for scene representation that contributes to the large scenes rendering.

  Based on the algorithm mentioned above, we leverage optimizations in both the system ([LandMarkSystem](https://github.com/InternLandMark)) and operators ([Flash3DGS](https://github.com/InternLandMark)) to reduce the computational requirements for training and rendering by two orders of magnitude compared to the previous generation.

  We further expand the model's editable capabilities and have launched a public experiential project, called [CityEyes](https://github.com/InternLandMark).

## Models

- [GridNerf](https://github.com/InternLandMark/LandMark): Grid-guided Neural Radiance Fields for Large Urban Scenes.
- [Scaffold-GS](https://github.com/city-super/Scaffold-GS): Structured 3D Gaussians for View-Adaptive Rendering.
- [Octree-GS](https://github.com/city-super/Octree-GS): Towards Consistent Real-time Rendering with LOD-Structured 3D Gaussians.

## Dataset
- [MatrixCity](https://github.com/city-super/MatrixCity): A Large-scale City Dataset for City-scale Neural Rendering and Beyond.

## Toolchain
- [LandMarkSystem](https://github.com/InternLandMark): Coming soon...
- [Flash3DGS](https://github.com/InternLandMark): Coming soon...

## Applications
- [CityEyes](https://github.com/InternLandMark): Coming soon...
