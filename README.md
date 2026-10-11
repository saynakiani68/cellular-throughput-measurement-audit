
# Before Learning from Cellular Traces

### Auditing Throughput Semantics and Measurement Timing in a Public 5G/LTE Dataset

**Author:** Sayna Kiani  
**Affiliation:** Universitat Politècnica de Catalunya (UPC), Barcelona, Spain  
**Conference:** ACM CoNEXT 2026 Student Workshop (CoNEXT-SW '26)  
**Status:** Accepted — publication forthcoming

## Overview

This study investigates the internal consistency of downlink throughput measurements in publicly available 5G/LTE cellular traces.

We reconstruct reported throughput from received-byte counts using an empirically inferred nominal 0.5-second accounting duration and examine discrepancies across two collection days.

## Key Findings

- Analyzed 23,865 downlink observations across 102 measurement intervals.
- Found strong agreement between reported and reconstructed throughput (Pearson correlations above 0.9997).
- Observed median absolute reconstruction residuals of 0.000368 Mbps on both days.
- Identified a small fraction of observations with residuals exceeding 5 Mbps.
- Found that exceptional residuals differ in timing and interval-level distribution across collection days.

## Why This Matters

Public cellular traces are often used to train machine-learning models. Understanding measurement semantics and timing is important before interpreting network behavior or developing predictive models.

This study provides an internal consistency audit rather than independent throughput ground truth. The impact of the observed discrepancies on machine-learning performance remains an open question.

## Paper

**Accepted at ACM CoNEXT 2026 Student Workshop.**

[Read the paper (PDF)](paper.pdf)

The official ACM Digital Library link will be added after publication.

## Reproducibility

Analysis code and reproducibility materials may be added to this repository after validation.

## Contact

**Sayna Kiani**  
[GitHub](https://github.com/saynakiani68) | [LinkedIn](https://www.linkedin.com/in/sayna-kiani)
