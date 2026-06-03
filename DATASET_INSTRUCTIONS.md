# Dataset Instructions

This repository does not redistribute the datasets used in the experiments.

## NYU Depth V2

NYU Depth V2 is used for indoor monocular depth experiments. The notebook contains the subset-preparation and validation steps required for the project workflow.

## KITTI Depth Selection

The KITTI selected-validation split is used only for outdoor cross-domain evaluation. No KITTI image is used for training, checkpoint selection, or hyperparameter tuning.

To reproduce the KITTI experiments:

1. Download the official KITTI depth-selection archive from the KITTI Vision Benchmark Suite.
2. Place the ZIP archive in the expected project data directory.
3. Run the KITTI extraction and evaluation cells in the notebook.

Large dataset archives, pretrained model binaries, and experiment checkpoints are intentionally excluded from this repository.
