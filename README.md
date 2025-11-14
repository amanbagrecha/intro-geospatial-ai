# Introduction to Geospatial AI

This workshop introduces geospatial instance segmentation using PyTorch and TorchGeo. You'll learn to:

1. Load and explore the NWPU VHR-10 (Very High Resolution, 10 classes) remote sensing dataset
2. Understand images, bounding boxes, and instance masks
3. Build and train a Mask R-CNN model for instance segmentation
4. Visualize predictions and evaluate model performance

## Setup Python Environment

### Prerequisites

Install [uv](https://github.com/astral-sh/uv) for Python package management:

```bash
# macOS/Linux
curl -LsSf https://astral.sh/uv/install.sh | sh

# Windows
powershell -c "irm https://astral.sh/uv/install.ps1 | iex"
```

### Environment Setup

1. Sync dependencies:
   ```bash
   uv sync
   ```

2. Activate the virtual environment:
   ```bash
   # Windows
   .venv\Scripts\activate

   # macOS/Linux
   source .venv/bin/activate
   ```

## Workshop Materials

### Slides

[View Workshop Slides](https://docs.google.com/presentation/d/19Kn1IQun0jHrmVzJ4z9W1hhv3c8Z7pFrRpwiPJ8Fg-E/edit?slide=id.g3a29650c99a_0_0#slide=id.g3a29650c99a_0_0)

### Notebook

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1YfhqSKHiuvqaUP0WRhJVqEKvHBeAvXZM#scrollTo=6V69swLd1jlR)

The notebook is also available in this workspace as [torchgeo_vhr10_maskrcnn_workshop.ipynb](torchgeo_vhr10_maskrcnn_workshop.ipynb)

## Topics Covered

- Introduction to remote sensing
- Applications of remote sensing
- Data download from STAC (SpatioTemporal Asset Catalogs)
- Geospatial AI techniques (instance segmentation)
- Hands-on demo with the VHR-10 dataset