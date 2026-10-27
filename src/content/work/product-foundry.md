---
title: 'Product Foundry'
description: 'Data pipeline and curation frontend for retail product cataloging, GTIN matching, and planogram exports.'
category: 'Retail data'
tech: ['Python', 'FastAPI', 'PostgreSQL', 'Playwright']
year: 2026
role: 'Data platform'
client: 'Retail Plano'
order: 2
featured: true
---

## Overview

Product Foundry scrapes retailer product data, processes it into a schema-mapped catalog, downloads and cleans product images, and supports manual curation through a web UI.

## Highlights

- Scrapers and image pipeline for multiple UAE retailers
- Postgres catalog with provenance and GTIN matching
- Curation frontend for dimensions and product facts
- Planogator bridge export for dimensioned products

## Status

See the `retail` repository's `pipelines/product-foundry` folder.
