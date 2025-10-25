---
title: "Text-RSSR: Text-Conditioned Remote Sensing Super-Resolution with Cross-Modal Learning"
collection: publications
category: journals
permalink: /publication/2025-08-01-textrssr
excerpt: 'Leveraging textual and semantic guidance to enhance feature aligning in remote sensing super-resolution tasks.'
date: 2025-08-01
---

[**Get PDF**](textrssr_paper.pdf)

**THIS WORK IS UNFINISHED**.

**Abstract**:&emsp; Super-resolution of remote sensing images (RSSR) seeks to reconstruct high-resolution content from low-resolution inputs, thereby providing critical detail for tasks such as environmental monitoring, urban mapping, and land-cover analysis. While deep learning-based RSSR methods have recently advanced super-resolution performance, they remain limited in effectively capturing semantic context. Most existing approaches rely solely on visual information, which often leads to over-smoothed textures, inadequate structural detail, and poor generalization across diverse landscapes. To address these challenges, this paper proposes Text-RSSR, a text-conditioned RSSR framework that introduces textual and semantic guidance through cross-modal learning. By leveraging text captions and CLIP embeddings, the model incorporates high-level contextual priors to iteratively refine visual features and enhance reconstruction quality. This integration of linguistic and visual information enables the network to achieve a stronger balance between fine detail restoration and semantic consistency. The effectiveness of Text-RSSR is validated through extensive experiments on three public RSSR datasets, where it achieves state-of-the-art performance with PSNR indexes of 16.3632 dB on Alsat-2B dataset, 27.4904 dB on UC Merced Land Use Dataset, and 27.4089 dB on AID. The implementation will be made publicly available at https://github.com/haoyangofficial/textrssr.

![1](/images/publications/textrssr/archi.jpg)