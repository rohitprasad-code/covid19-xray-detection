# covid19-xray-detection
This repository presents a study leveraging pre-trained CNN models (VGG-16, InceptionV3, DenseNet201, ConvNeXtXLarge, EfficientNetV2S) for classifying chest X-ray images. Our study, conducted with a diverse dataset, demonstrates the potential of deep learning in early and precise COVID-19 detection. DenseNet201 emerged as a top performer, highlighting the effectiveness of automated methods in addressing the global health crisis.

## Dataset
Dataset used in this study is available at [Kaggle](https://www.kaggle.com/datasets/rohitprasad612/covid19-dataset-x-ray/data). The dataset contains 137 COVID-19, 90 viral pneumonia, and 90 normal chest X-ray images.

## Installation

1. Clone the repository.

```bash
git  clone https://github.com/rohitprasad-code/covid19-xray-detection.git && cd covid19-xray-detection
```

2. Install the environment.

```bash
conda  create  -n  covid19 python=3.8  -y
conda  activate  covid19 
```

3. Install the dependencies.

```bash
pip  install  -r  requirements.txt
```

4. Use the notebook to train the model and test it.

```bash
jupyter  notebook
```
