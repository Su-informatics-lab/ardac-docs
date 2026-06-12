---
title: Use the API
---

# Use the API

ARDaC APIs allow approved users and developers to search metadata, retrieve file information, automate workflows, and integrate ARDaC services with external tools.

## Typical API uses

- Search datasets and metadata programmatically
- List files associated with an approved dataset
- Build reproducible download or analysis workflows
- Integrate ARDaC metadata with internal systems
- Support dashboards, quality checks, and reporting

## Authentication

Most API operations require authentication. Some endpoints may also require dataset-specific authorization.

## API usage guidance

Use stable identifiers when referencing datasets or files. Avoid hard-coding temporary URLs. Handle pagination, rate limits, errors, and expired credentials gracefully.

## Example workflow

1. Authenticate with ARDaC.
2. Query metadata for a dataset or project.
3. Confirm access permissions.
4. Retrieve file manifests or signed access links.
5. Run downstream scripts in an approved environment.
