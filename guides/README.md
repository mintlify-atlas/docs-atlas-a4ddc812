# Mage Tutorial Guides

This directory contains comprehensive, step-by-step tutorial guides for building data pipelines with Mage.

## Available Tutorials

### 1. Building Your First Pipeline (`first-pipeline.mdx`)
- **Duration**: ~10 minutes
- **Level**: Beginner
- **Topics**: Basic pipeline creation, data loaders, transformers, data exporters
- **What you'll build**: A simple ETL pipeline that fetches data from an API, transforms it, and exports to a file
- **Lines**: 420

### 2. ETL Workflow (`etl-workflow.mdx`)
- **Duration**: ~30 minutes  
- **Level**: Intermediate
- **Topics**: Multi-source data loading, complex transformations, data quality checks, aggregations
- **What you'll build**: A production-ready ETL pipeline with PostgreSQL, API, and CSV sources
- **Lines**: 732

### 3. Streaming Pipeline (`streaming-pipeline.mdx`)
- **Duration**: ~45 minutes
- **Level**: Advanced
- **Topics**: Real-time data processing, Kafka integration, windowing, backpressure handling
- **What you'll build**: A streaming pipeline for real-time event processing with Kafka
- **Lines**: 822

### 4. dbt Integration (`dbt-pipeline.mdx`)
- **Duration**: ~30 minutes
- **Level**: Intermediate
- **Topics**: dbt setup, SQL models, testing, combining dbt with Python, snapshots
- **What you'll build**: A data transformation pipeline using dbt models orchestrated by Mage
- **Lines**: 819

### 5. ML Pipeline (`ml-pipeline.mdx`)
- **Duration**: ~60 minutes
- **Level**: Advanced
- **Topics**: Feature engineering, model training, validation, batch inference, monitoring
- **What you'll build**: An end-to-end ML pipeline for customer churn prediction
- **Lines**: 1,032

## Tutorial Features

All tutorials include:

✅ **Real code examples** from the actual Mage codebase
✅ **Step-by-step instructions** with detailed explanations
✅ **Mintlify components** (Steps, CodeGroup, Note, Tip, Accordion)
✅ **Proper frontmatter** with title, description, and icon
✅ **Testing and validation** examples
✅ **Troubleshooting sections**
✅ **Next steps and related resources**

## Code Sources

These tutorials were created by analyzing the actual Mage source code:
- `mage_ai/data_preparation/models/` - Pipeline and block models
- `mage_ai/streaming/` - Streaming sources and sinks
- `mage_ai/data_preparation/templates/` - Block templates
- `docs/guides/dbt/` - dbt integration documentation
- `example.ipynb` - Example notebooks

## Total Content

- **Total lines**: 3,825
- **Total tutorials**: 5
- **Estimated learning time**: ~2.5 hours

## Getting Started

1. Start with `first-pipeline.mdx` if you're new to Mage
2. Progress to `etl-workflow.mdx` for production patterns
3. Explore `streaming-pipeline.mdx` or `dbt-pipeline.mdx` based on your use case
4. Build ML workflows with `ml-pipeline.mdx`

Each tutorial builds on concepts from previous ones while remaining self-contained.
