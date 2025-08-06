---
title: "Redistributed allele frequencies for CIWD 3.0.0"
date: 2025-05-22
draft: false
description: "A dataset for the HLA community designed for accuracy."
tags: ["bioinformatics", "project", "hla"]
---



In the HLA community, CIWD 3.0.0 is an industry-standard allele frequency dataset published in 2021 that is used to define alleles of importance in diagnostic kits. Its use can be seen from underpinning modern HLA typing kit design to international laws and regulations surrounding organ transplantation. Despite its widespread adoption, a major problem is that the data is not standardized and reflects a wide range of differences from underlying technology to operational bias. In May 2025, at the European Federation of Immunogenetics (EFI) conference, I presented a method that aimed to practically solve this problem and offer a solution to researchers and companies worldwide.

## The Challenge: Standardize the dataset

The CIWD 3.0.0 dataset is comprised of millions of HLA typing results from labs across the world. When a technician submits the result, they don't always submit the genotype because oftentimes the typing technology is not enough to distinguish it. Because of this, they usually will claim that the typing result belongs to a group of alleles, such as a group of alleles that share the same coding sequence or alleles that share the same protein sequence. In HLA, there are many different "groups" that are widely used to define ambiguities that are unresolvable with a lab's available technology. This creates a problem: since only 4.6% of typing results are genotypes, most allele frequencies in CIWD 3.0.0 are inaccurate.

The goal of this project was to create an algorithm that approximates the genotypes of all of the unresolvable typing results to have a true dataset of genotypes. Using this algorithm, we present a dataset with significantly better accuracy that is validated using independent datasets.

## Key Skills & Technologies Demonstrated

This project has been an invaluable learning experience, allowing me to apply and strengthen a diverse set of skills:

*   **Algorithm Development & Optimization:** Designed and implemented a novel algorithm to resolve data ambiguity and approximate genotypes from complex, non-standardized biological data.
*   **Data Validation:** Validated the accuracy of the newly generated dataset against independent sources, ensuring the reliability and robustness of the results.
*   **Scientific Communication & Presentation:** Presented complex methodologies and findings to an international audience of experts at a prestigious scientific conference (EFI 2025).
*   **Identified and Solved a Critical Industry Problem:** Recognized a significant flaw in a foundational dataset and took the initiative to develop a practical, high-impact solution.
*   **Created Actionable Data:** Transformed a dataset with over 95% ambiguity into a high-fidelity resource, enabling more accurate HLA typing, which directly impacts diagnostic kit design and organ transplant regulations.
