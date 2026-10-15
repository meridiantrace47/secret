# Meridian Logistics Data Toolkit

A lightweight Python-based toolkit for processing shipment records, inventory data, transaction logs, and automated reporting.

## Overview

Meridian Logistics Data Toolkit was originally developed to support small-scale logistics operations, including shipment tracking, inventory reconciliation, and delivery reporting.

The toolkit processes structured CSV and JSON datasets and generates summary reports for internal operational reviews.

Several components were adapted from earlier projects maintained under the alias `meridian47`.

## Features

- Shipment and delivery record processing
- Inventory reconciliation and discrepancy detection
- Transaction reference validation
- Automated CSV and JSON reporting
- Timestamp normalisation across multiple data sources
- Batch identification and tracking

## Project Structure

```text
meridian-logistics-toolkit/
├── README.md
├── src/
│   ├── shipment_parser.py
│   ├── inventory_validator.py
│   └── transaction_report.py
├── data/
│   └── sample_shipments.csv
├── docs/
│   └── operational_notes.md
├── config/
│   └── settings.example.json
└── CHANGELOG.md
```

## Development Notes

The project was initially maintained as a private collection of scripts before being reorganised into a public repository.

Earlier versions were associated with the developer alias `meridian47`, while the current development environment uses `meridian_trace47`.

Some historical datasets contain shipment references using internal identifiers such as `BL-047`, `NX-219`, and `CR-081`.

These identifiers were retained to preserve compatibility with archived reporting formats.

## Sample Dataset

The `data/sample_shipments.csv` file contains fictional shipment records for testing the processing functions.

Certain historical entries include incomplete consignee information, inconsistent declared weights, and repeated transaction references.

These records are retained as test cases for data validation.

## Version History

**Version 1.3 — September 2025**
- Updated shipment reconciliation functions
- Improved handling of incomplete delivery records

**Version 1.2 — July 2025**
- Added support for batch reference tracking
- Updated transaction reporting

**Version 1.1 — April 2025**
- Introduced inventory discrepancy detection

**Version 1.0 — January 2025**
- Initial project release

## Maintainer

**Developer:** Daniel M.  
**GitHub Alias:** meridian_trace47  
**Previous Alias:** meridian47  
**Contact:** meridiantrace47@gmail.com

## License

MIT License
