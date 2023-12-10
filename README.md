# Search Product Benchmark

## Setup

```
mkdir dataset output
curl -L -o shopping_queries_dataset_products.parquet https://github.com/amazon-science/esci-data/raw/main/shopping_queries_dataset/shopping_queries_dataset_products.parquet
curl -L -o shopping_queries_dataset_examples.parquet https://github.com/amazon-science/esci-data/raw/main/shopping_queries_dataset/shopping_queries_dataset_examples.parquet
```

## Notebooks

- [analysis-elasticsearch.ipynb](analysis-elasticsearch.ipynb)
- [analysis-opensearch.ipynb](analysis-opensearch.ipynb)
