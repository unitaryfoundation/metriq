# Metriq Platform

This repository is the umbrella for Metriq platform architecture and cross-component documentation.

## Architecture Overview

```mermaid
flowchart LR

    G[metriq-gym] --> D[metriq-data] --> W[metriq-web]

    click G "https://github.com/unitaryfoundation/metriq-gym" "Open metriq-gym" _blank
    click D "https://github.com/unitaryfoundation/metriq-data" "Open metriq-data" _blank
    click W "https://github.com/unitaryfoundation/metriq-web" "Open metriq-web" _blank
```

## Components

| Repository | Purpose | License |
| --- | --- | --- |
| [unitaryfoundation/metriq-gym](https://github.com/unitaryfoundation/metriq-gym) | Benchmark protocol definitions and execution tooling | Apache-2.0 |
| [unitaryfoundation/metriq-data](https://github.com/unitaryfoundation/metriq-data) | Versioned, schema-enforced benchmark datasets | CC-BY-4.0 |
| [unitaryfoundation/metriq-web](https://github.com/unitaryfoundation/metriq-web) | Metrics dashboards, raw-data tables, and detailed views | Apache-2.0 |

## Issues

Please report issues in the relevant component repository. If you're unsure which one is correct, open the issue here and it will be triaged.

## Roadmap

For a detailed roadmap of the Metriq platform, please refer to the [Metriq Roadmap 2026](./docs/roadmap/2026.md) document.

## Metriq Paper
_Preprint_: Alessandro Cosentino, Changhao Li, Vincent Russo, Bradley A. Chase, Tom Lubinski, Siyuan Niu, Neer Patel, Nathan Shammah, and William J. Zeng. _Metriq: A Collaborative Platform for Benchmarking Quantum Computers_, [arXiv:2603.08680](https://arxiv.org/abs/2603.08680) (2026).
