# Project Setup

## 1. Environment Setup
Create a virtual environment and install the required dependencies:

```bash
pip install -r requirements.txt
```
## 2. Dataset

### Images
Download the COCO2017 image dataset from [this link](https://www.kaggle.com/datasets/awsaf49/coco-2017-dataset?resource=download).

### Annotations
Download the LVIS annotation files from [this link](https://www.lvisdataset.org/dataset).

### Update constants
Create a python file `constants.py` and paste the following constants with updated paths.

```python
COCO2017_TRAIN_PATH = "<path_to_train_dataset_folder>"
COCO2017_VAL_PATH   = "<path_to_val_dataset_folder>"
COCO2017_TEST_PATH  = "<path_to_test_dataset_folder>"
TRAIN_ANNOT_PATH = "<path_to_train_annotations_file>"
VAL_ANNOT_PATH   = "<path_to_val_annotations_file>"
TEST_ANNOT_PATH  = "<path_to_test_annotations_file>"
```