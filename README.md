# US Sovereign Wealth Fund Proposal

A comprehensive white paper analyzing the feasibility and design of a United States Sovereign Wealth Fund.

## Contents

- `US_SWF_Proposal_WhitePaper.md` - Full manuscript in Markdown format
- `US_SWF_Proposal_WhitePaper.pdf` - Compiled PDF version

## Overview

This white paper examines the February 2025 executive order calling for the creation of a US Sovereign Wealth Fund, analyzing:

- Global SWF landscape and best practices
- Funding mechanisms and challenges for a deficit-running nation
- Governance frameworks drawing on Santiago Principles
- Proposed dual-account structure (Strategic + Domestic Investment)
- Implementation roadmap and legislative requirements

## Building the PDF

To regenerate the PDF from the Markdown source:

```bash
pandoc US_SWF_Proposal_WhitePaper.md -o US_SWF_Proposal_WhitePaper.pdf --pdf-engine=xelatex --toc --toc-depth=2 -V geometry:margin=1in -V fontsize=11pt
```

## License

All rights reserved.
