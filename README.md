# FoundationPose-Dataset

Red satellite models captured from diverse viewing angles. Source code for our paper: 6D Satellite Pose Estimation Method based on FoundationPose.

##  Dataset Structure
```text
FoundationPose-Dataset/
├── train/          # 训练集图片 (510 张)
├── val/            # 验证集图片 (50 张)
└── test/           # 测试集图片 (48 张)
##  Annotation Format
Format: TXT 
Content: Each image is paired with a 6D pose annotation file containing:
Rotation: Quaternion `(w, x, y, z)` 
Translation: Translation vector `(tx, ty, tz)` in meters.
Storage: Annotation files share the same base name as the images and are stored in the corresponding dataset folders.

##  Usage
This dataset is released as a standalone resource to facilitate reproducibility of the experiments reported in our paper. The full implementation details and network architecture are provided in the manuscript.
