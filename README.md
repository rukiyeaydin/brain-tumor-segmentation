### Dataset

This project was developed in Google Colab. The dataset is downloaded automatically using `kagglehub` with the following code:

```python
import kagglehub
path = kagglehub.dataset_download("mateuszbuda/lgg-mri-segmentation")
```

If you are running the code outside of Google Colab, make sure you have installed `kagglehub`:

```bash
pip install kagglehub
```

The dataset will be downloaded automatically to your local environment and the `path` variable will contain the dataset directory.

Dataset source: https://www.kaggle.com/datasets/mateuszbuda/lgg-mri-segmentation
