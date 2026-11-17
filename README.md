# Alzheimer’s Disease Classification

A final-year Streamlit prototype that explores tabular data and demonstrates a machine-learning prediction workflow. It also includes an experimental MRI/CT image tab built around a brain-tumor model.

The image model predicts tumor classes, which the original interface relabels as dementia categories. The accuracy shown in that tab is randomly generated. Treat the application as coursework and do not use it for clinical decisions.

## Run locally

From the repository root, install the dependencies and start Streamlit.

```sh
python -m pip install -r requirements.txt
python -m streamlit run main.py
```

Before launching, place your local copy of the original `Alzheimer.csv` in the repository root. The app loads it at startup. To use the experimental image tab, also place the original `BrainTumuorModel.h5` under `Models/`. The repository excludes the datasets and model weights because their redistribution terms could not be verified.

The original project references [MRI Deep Analysis by MainakRepositor](https://github.com/MainakRepositor/MRI-Deep-Analysis).
