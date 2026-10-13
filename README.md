# PointNet++-Guided Vascular Path Planning

This repository contains code for endpoint-conditioned path planning in 2D vascular images. A PointNet++ model predicts route-related guidance from an image-derived point set, and Pixel RRT* uses this guidance to search for a feasible path in the image.

## Overview

1. Provide a vascular image and start/end points.
2. Build a task-conditioned point-set representation from the image.
3. Predict route guidance with PointNet++.
4. Use the guidance to bias Pixel RRT* path planning.

