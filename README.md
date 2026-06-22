# S3 Data Lake 🏔️

S3 data lake architecture with partitioning, lifecycle, and Athena optimization.

## Architecture

```
Ingestion → S3 Raw → Processed → S3 Curated → Athena/Glue
```

## Partitioning Strategy

```
s3://data-lake/
  raw/year=2024/month=01/day=15/
  curated/year=2024/month=01/day=15/
```

## License

Apache 2.0