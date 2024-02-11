# Search Product Benchmark

## Setup

```
mkdir dataset output
curl -L -o dataset/shopping_queries_dataset_products.parquet https://github.com/amazon-science/esci-data/raw/main/shopping_queries_dataset/shopping_queries_dataset_products.parquet
curl -L -o dataset/shopping_queries_dataset_examples.parquet https://github.com/amazon-science/esci-data/raw/main/shopping_queries_dataset/shopping_queries_dataset_examples.parquet
```

## Notebooks

- [diff-check-elasticsearch.ipynb](diff-check-elasticsearch.ipynb)
- [diff-check-opensearch.ipynb](diff-check-opensearch.ipynb)
