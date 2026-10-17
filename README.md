# PointNet++-Guided Vascular Path Planning

Code and pretrained models will be released upon acceptance.

## Method Overview

1. Provide a vascular image and start/end points.
2. Build a task-conditioned point-set representation from the image.
3. Predict route guidance with PointNet++.
4. Use the guidance to bias Pixel RRT* path planning.
