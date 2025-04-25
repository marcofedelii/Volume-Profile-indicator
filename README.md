# Volume Profile – MT4 Indicator

## Overview
**Volume Profile** is a compiled indicator for MetaTrader 4 that calculates and displays key volume-based price levels:
- **POC (Point of Control)**
- **VAH (Value Area High)**
- **VAL (Value Area Low)**

The calculation is based on historical volume distribution over a configurable window of bars. The indicator divides the price range into bins and allocates volume accordingly, making it an essential tool for traders utilizing volume analysis and market structure in their strategies.

This repository provides:
- The compiled `.ex4` file ready for installation
- Full technical documentation in both Italian and English

The source code is proprietary and is not included in this repository.

## Installation
1. Copy `VolumeProfile.ex4` to your `MQL4/Indicators/` directory
2. Restart MetaTrader 4
3. Add the indicator to any chart and configure the input parameters as needed

## Documentation
Full technical documentation is available in the `docs/` folder:
- `Volume Profile_ panoramica tecnica ITA.pdf` – Technical report (Italian)
- `Volume Profile_ A Technical
Overview ENG.pdf` – Technical report (English)

Included in the documents:
- Technical breakdown of the indicator logic
- Integration examples with Expert Advisors (EAs)
- Description of input parameters and internal buffers

## License
This indicator is provided in compiled form only.

You may:
- Use it for personal and educational purposes within MetaTrader 4

You may not:
- Redistribute, decompile, reverse engineer, or use it commercially without prior written permission

See `LICENSE` for full license terms.

## Author
Developed by **Marco Fedeli**
Quantitative Trader and AI Architect
Contact: marcofedeli05@icloud.com

