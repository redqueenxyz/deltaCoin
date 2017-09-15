## predCoin

Maybe Deep Learning can help us trade cryptocoins better? Idk. Let's find out. 

### Env

Currently built with Google Cloud Datastore, BigQuery, Tensorflow, Keras, for application with the Kraken Exchange API.
    
### Intro 

|||
|---|---|
|`/data`| Datasets to download from, temporarily store, and eventually uploadting into BigQuery. 
|`/download`| Functions to save responses into a Database as individual datasets in whatever format (`.csv`, `.json`, etc.)
| `/models`| Different deep learning models we might build. Query that dataset with Google Bigquery with models in `/models`. 
|`/examples`| Models we're experimenting with. 

### Data

We intend to use the following datasets at present, and then scale up from there!

| status  | description  | timeframe  | source |
|---|---|---|---|
| ![](https://img.shields.io/badge/google_big_query-uploaded-green.svg?style=flat)  | Kraken XBT/USD exchange OHLP Data | minute | [This Amazing Kaggle Dataset](https://www.kaggle.com/mczielinski/bitcoin-historical-data)  |   |   
| ![](https://img.shields.io/badge/google_big_query-!uploaded-red.svg?style=flat)  | XBT Blockchain Metrics | minute? | [TBD]() |   |   