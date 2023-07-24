This repo contains miscellaneous project notebooks (work samples).


## pylift_scoring_final.ipynb
This notebook demonstrates how to perform inference from a pre-trained uplift model using Google Cloud Platform (GCP)
- retrieve a model saved as an artifact on Google Cloud Storage (GCS)
- select data for prediction using BigQuery
- invoke prediction (inference)
- apply deciles from preset thresholds to the predicted uplift scores
- save the uplift scores and deciles to a persistent table in BigQuery  

The model in this case was produced using [pylift] (open source package published by Wayfair).

[pylift]: https://github.com/wayfair/pylift/
