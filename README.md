# Filipino SMS Scam Detector

An experimental machine learning and cybersecurity project exploring the classification of Filipino SMS messages as scam or non-scam using traditional machine learning techniques.

**Status: Experimental — Development Paused**

The dataset requires further cleaning and validation before the model can be reliably evaluated or deployed.

## Datasets

This project uses the following publicly available datasets:

- [Tagalog SMS Dataset](https://www.kaggle.com/datasets/onzero0/tagalog-sms) by onzero0
- [Philippine Spam/Scam SMS](https://www.kaggle.com/datasets/bwandowando/philippine-spam-sms-messages) by bwandowando
- [Filipino Gossip Dataset](https://huggingface.co/datasets/jhenberthf/filipino-gossip-dataset) by jhenberthf

These datasets vary in format and relevance. Further filtering, label validation, and refinement are needed to ensure the data is suitable for scam detection.

## Project Structure

- `main.ipynb` — Notebook for data exploration, preprocessing, model training, and evaluation.
- `dataset.csv` — Initial dataset.
- `datasetV2.csv` — Revised dataset.

## Limitations

This project is not deployed and should not be used for real-world scam detection. Dataset quality and representativeness remain key limitations, and experimental evaluation results may not reflect real-world performance.