# Week2: Masks where they don't exist

## Overview

You are given a real-world scene captured from multiple viewpoints. The scene has already been processed using COLMAP, and sparse camera poses and calibration parameters are provided.

Your objective is to:

1. Reconstruct the scene using 3D Gaussian Splatting (3DGS).
2. Use provided object instance masks to isolate specific objects from the scene and remove all background geometry.
3. Render the resulting object-only scene from novel viewpoints.
4. Generate accurate segmentation masks for each rendered novel view.

Data - [Drive](https://drive.google.com/file/d/1YPDMC2yN4mXQCczCYPJgjLFz5W0dxxWf/view?usp=sharing)
