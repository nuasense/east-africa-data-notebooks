# East African agricultural data: starter notebooks

One notebook per free data sample from [NuaSense](https://agriculture-data.com): market prices, farm input prices, satellite crop condition, the crop season calendar, cropland and crop mix, and regulation signals for Kenya, Uganda, Tanzania and Rwanda. Each notebook loads its table, answers two or three questions with it, and shows how to get the full series.

| Notebook | Colab | Kaggle | Data |
|---|---|---|---|
| Farm input prices, Kenya and Uganda | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/nuasense/east-africa-data-notebooks/blob/main/east-africa-farm-input-prices-starter.ipynb) | [Kaggle](https://www.kaggle.com/code/nuasense/east-africa-farm-input-prices-starter) | [Hugging Face](https://huggingface.co/datasets/nuasense/east-africa-farm-input-prices) |
| Crop season calendar from satellite NDVI | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/nuasense/east-africa-data-notebooks/blob/main/east-africa-season-onset-ndvi-starter.ipynb) | [Kaggle](https://www.kaggle.com/code/nuasense/east-africa-crop-season-calendar-ndvi-starter) | [Hugging Face](https://huggingface.co/datasets/nuasense/east-africa-season-onset-ndvi) |
| Cropland NDVI by county | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/nuasense/east-africa-data-notebooks/blob/main/east-africa-cropland-ndvi-starter.ipynb) | [Kaggle](https://www.kaggle.com/code/nuasense/east-africa-cropland-ndvi-by-county-starter) | [Hugging Face](https://huggingface.co/datasets/nuasense/east-africa-cropland-ndvi) |
| Maize and fertilizer prices by county | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/nuasense/east-africa-data-notebooks/blob/main/kenya-maize-and-fertilizer-prices-by-county.ipynb) | [Kaggle](https://www.kaggle.com/code/nuasense/kenya-maize-and-fertilizer-prices-by-county) | [Hugging Face](https://huggingface.co/datasets/nuasense/kenya-county-food-and-fertilizer-prices) |
| Fertilizer affordability by county | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/nuasense/east-africa-data-notebooks/blob/main/kenya-county-fertilizer-affordability-starter.ipynb) | [Kaggle](https://www.kaggle.com/code/nuasense/kenya-county-fertilizer-affordability-starter) | [Hugging Face](https://huggingface.co/datasets/nuasense/kenya-county-fertilizer-affordability) |
| Cropland extent by county | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/nuasense/east-africa-data-notebooks/blob/main/kenya-county-cropland-extent-starter.ipynb) | [Kaggle](https://www.kaggle.com/code/nuasense/kenya-county-cropland-extent-starter) | [Hugging Face](https://huggingface.co/datasets/nuasense/kenya-county-cropland-extent) |
| Crop mix by county (pilot) | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/nuasense/east-africa-data-notebooks/blob/main/kenya-county-crop-mix-pilot-starter.ipynb) | [Kaggle](https://www.kaggle.com/code/nuasense/kenya-county-crop-mix-pilot-starter) | [Hugging Face](https://huggingface.co/datasets/nuasense/kenya-county-crop-mix-pilot) |
| Agricultural regulation signals | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/nuasense/east-africa-data-notebooks/blob/main/east-africa-agri-regulation-signals-starter.ipynb) | [Kaggle](https://www.kaggle.com/code/nuasense/east-africa-agri-regulation-signals-starter) | [Hugging Face](https://huggingface.co/datasets/nuasense/east-africa-agri-regulation-signals) |

In Colab or on your own machine a notebook reads its table straight from Hugging Face; on Kaggle it reads the attached dataset. Nothing to download first.

## The data

The samples are free for non-commercial use (CC BY-NC 4.0); each data card names its sources. They are cut from the datasets on the NuaSense platform: daily market prices since 2021, weekly satellite indices since 2018, crop production by county, regulation and news signals. Fields and filters: [agriculture-data.com](https://agriculture-data.com/datasets/). An API key with a free monthly allowance comes from [platform.nuasense.com](https://platform.nuasense.com/start); in Python, `pip install nuasense`.

## Licence

The notebooks' code is MIT. The data keeps the licence of its data card.

NuaSense Limited, Nairobi · info@nuasense.com
