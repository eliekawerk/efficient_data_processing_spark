# Efficient Data Processing in Spark 

## Prerequisites

## Setup

- python script 
- create and count sql to docker container 
- tpch-dbgen
 
## Data model

## Running queries

- make spark sql

## Stopping containers

## Acknowledgements

<!--
Data: https://github.com/databricks/tpch-dbgen
Generate data => mount into shared volume => access via spark 

Note: tpch dbgen issues with mac https://github.com/pola-rs/tpch

1. Load data into spark (docker data location /opt/spark/work-dir/tpch/tpch-dbgen/customer.tbl)
2. tables: customer.tbl lineitem.tbl nation.tbl   orders.tbl   part.tbl     partsupp.tbl region.tbl   supplier.tbl
3. DDL query
-->