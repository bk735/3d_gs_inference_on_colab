# 3D Gaussian Splatting Experiments

This repository contains experiments and results for **3D Gaussian Splatting (3D-GS)**, including training under dense and sparse view settings, along with visual comparisons and rendered outputs.



##  Repository Contents

* **3d_gs.ipynb**
  Notebook for training and rendering scenes using **3D Gaussian Splatting**.
  Includes experiments on both full-image datasets and sparse-view settings.
  Useful as a baseline with evaluation metrics.

* **comparison_test_video.mp4**
  A comparison video demonstrating two training setups:

  * **Left:** Model trained on 169 images and tested on 25 images
  * **Right:** Model trained on 7 evenly spaced images and tested on 25 images

* **point_cloud_image.png**
  Rendered image generated from output point clouds using Supersplat.

* **sparse_image.png**
  Rendered image from sparse-view training using Supersplat.

---

##  Results

### Comparison Video

<video src="comparison_test_video.mp4" controls width="600"></video>

---

## 🖼️ Rendered Outputs

![Point Cloud Rendering](point_cloud_image.png)
![Sparse View Rendering](sparse_image.png)

---

##  Key Highlights

* Implementation of **3D Gaussian Splatting**
* Comparison between **dense vs sparse training**
* Visualization using **Supersplat**
* Includes baseline experiments with evaluation metrics

---

##  Notes

* Ensure all files are placed correctly in the `vis/` directory for proper rendering in GitHub.
* For large files (e.g., videos), consider compression or Git LFS if needed.



##  Acknowledgment

This work is part of experimentation and learning in modern **neural rendering techniques**.
