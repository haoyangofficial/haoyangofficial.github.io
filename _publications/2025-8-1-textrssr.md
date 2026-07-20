---
title: "Text-RSIR: A Text-Guided Framework for Efficient Remote Sensing Image Transmission and Reconstruction"
collection: publications
category: journals
permalink: /publication/2025-08-01-textrssr
excerpt: 'Low-bandwidth and information-preserving transmission and reconstruction via LR–text pairs.'
date: 2025-08-01
---

[**Get PDF on arXiv**](https://arxiv.org/pdf/2605.15558)

**Abstract**:&emsp; High-resolution remote sensing imagery is critical for environmental monitoring, urban mapping, and land cover analysis, but its transmission is often hindered by limited bandwidth and high communication costs. Conventional pipelines transmit full-resolution pixel data, resulting in redundant and inefficient delivery. This paper proposes a text-guided remote sensing image transmission system that replaces complete high-resolution data with low-resolution images accompanied by compact textual descriptions. An onboard text generator produces spatial and semantic summaries, reducing the transmitted data volume to approximately 2\% of the original size. For ground-based reconstruction, a text-conditioned image restoration model is introduced, which leverages cross-modal learning to recover fine spatial details and maintain semantic coherence. Experimental results on the Alsat-2B, UC Merced Land Use, and Aerial Image datasets demonstrate that the proposed framework achieves reconstruction PSNRs of 16.36 dB, 26.87 dB, and 27.41 dB, respectively, enabling efficient and information-preserving image transfer for remote sensing applications. The implementation will be made publicly available at GitHub.

![1](/images/publications/textrssr/arch.jpg)