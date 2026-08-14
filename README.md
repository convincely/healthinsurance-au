# healthinsurance-au Dataform Project

Dataform project for Health Insurance Australia analytics pipeline.

## Setup

This project is configured to compile to BigQuery dataset `analytics_531718773`.

## Models

- **UnnestedData** — Unnested GA4 events with traffic source and experience step mappings. Incremental table partitioned by `event_date` with automatic 3-day lookback for late-arriving data.

## Documentation

See [Dataform docs](https://cloud.google.com/dataform/docs) for more information.
