# BDD100k Dataset

The original repo has been moved to https://github.com/bdd100k/bdd100k permanently.

---

In this repo, a feature to extract only lane lines is added. To do this, run;

```shell
python bdd100k\show_labels.py --image-dir datasets\path\to\images\100k\train --label datasets\path\to\bdd100k_labels_images_train.json --output_dir datasets\desired\path\to\lanes\100k\train --lane-only
```
