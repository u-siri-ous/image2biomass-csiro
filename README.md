# 🌾 CSIRO Image2Biomass: Repo for project submission

### Warning! The code you find may not run in environments besides Kaggle. This is because the submissions to the competition had to be made from a notebook version and not file upload.

This repo contains the code we did for the [Kaggle competition](https://www.kaggle.com/competitions/csiro-biomass), from the EDA, to the baseline to the final approaches. 

The competition arises from the **need to have a fast and reliable way to estimate biomass**, to make livestock and land live happily ever after. 

The (training) dataset is comprised of 357 images and a table containing:
- sample_id,
- image_path,
- Sampling_Date,
- State,
- Species,
- Pre_GSHH_NDVI,
- Height_Ave_cm,
- target_name,
- target

The testing dataset is **private**, and never accessible to us. 

Users report it contains about 800 images. It will have some metadata missing.


## Repo Tree

```
├── EDA + baseline/ 
│   ├── experimental/
│   │   ├── csiro-dataloader-model-GPU.ipynb
│   │   └── csiro-dataloader-model.ipynb
│   ├── csiro-baseline-nb.ipynb
│   ├── csiro-baseline-submission.ipynb
│   └── csiro-eda-preprocessing.ipynb
├── notebooks/
│   ├── inference-nb.ipynb
│   └── training-nb.ipynb
├── .gitattributes
├── .gitignore
├── csiro-dataloader-model-GPU-2.ipynb
├── LICENSE
└── README.md
```

`EDA + baseline/` contains the data analysis code and the baseline formation, with util notebooks in `experimental/`.

`/notebooks` contains the training notebook, the benchmark notebook and the inference notebook.

Model(s) weights and dataset are publicly available on Kaggle.
