# BigQuery

### General

* [General overview](https://cloud.google.com/blog/products/data-analytics/new-blog-series-bigquery-explained-overview): BigQuery Explained series great for intro
  * This series explains general overview
  * Basics of Collosus columnar storage
  * Optimizing queries by partitioning and clustering
  * How to get data -into> BQ
  * Understand SQL in BQ
* [Docs](https://cloud.google.com/bigquery/docs/introduction)
* [Under the hood](https://cloud.google.com/blog/products/bigquery/bigquery-under-the-hood)
* [Columnar storage](https://cloud.google.com/blog/products/bigquery/inside-capacitor-bigquerys-next-generation-columnar-storage-format)
* [Architecture](https://medium.com/google-cloud/the-12-components-of-google-bigquery-c2b49829a7c7) - topological map of BQ
* [Demo](https://www.youtube.com/watch?v=eOQ3YJKgvHE\&t=342s) talk about analyzing 1PB in few sec
* [15 things you didn't know about BQ](https://medium.com/google-cloud/15-awesome-things-you-probably-didnt-know-about-google-bigquery-6654841fa2dc)
* [BigQuery DDL](https://cloud.google.com/bigquery/docs/reference/standard-sql/data-definition-language)
* [Streaming insert](https://cloud.google.com/blog/products/bigquery/life-of-a-bigquery-streaming-insert)
* [Cloud game archi](https://cloud.google.com/architecture/cloud-game-infrastructure#streaming\_pipeline)

#### Sub components

* [Colossus](https://www.systutorials.com/colossus-successor-to-google-file-system-gfs/) - Storage engine
  * [Capacitor](https://cloud.google.com/blog/products/bigquery/inside-capacitor-bigquerys-next-generation-columnar-storage-format)
  * [Separation of storage and compute](https://cloud.google.com/blog/products/bigquery/separation-of-storage-and-compute-in-bigquery)
* [Dremel](https://research.google/pubs/pub36632/) - Execution engine
  * [Pipelined execution, smart scheduling](https://www.youtube.com/watch?v=UueWySREWvk) talk
* [Jupiter network](https://cloudplatform.googleblog.com/2015/06/A-Look-Inside-Googles-Data-Center-Networks.html) - separation of storage and compute ^
* Borg
