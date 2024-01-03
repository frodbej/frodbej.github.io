---
title: "MSc Capstone Project"
excerpt: "An image analysis pipeline for detecting different cell phenotypes in breast cancer cells. <br/><img src='/images/image_analysis.png'>"
collection: portfolio
---

Cell shape provides valuable information about the cellular phenotype and the cell’s physiological state due to the connection between morphology and phenotype. Thus, morphological analysis could allow us to understand relevant underlying mechanisms in diseases with an important morphological component such as cancer, particularly in the metastatic process.

Furthermore, advances in automated microscopy have made it possible to develop image-based high-throughput cell profiling assays, that allow to define complex cellular phenotypes through the extraction of multiple features for each cell of the population. Thus, with this approach, we can generate large quantities of data at population resolution and at single-cell resolution to identify genes involved in different biological processes and heterogeneous cell behaviors.

Based on the importance of cell shape dynamics on metastasis, we used a small interfering RNA library to specifically suppress the expression of more than 500 proteins related to the cytoskeleton on a metastatic cell line of triple-negative breast cancer to perform a cell profiling approach. The large amount of image data composed of fluorescence images of cells with silenced expression of each of the genes was processed using CellProfiler software, for which we meticulously crafted a processing pipeline that automatically extracts hundreds of cell features from thousands of images.

In this work we employed a mixed approach for the analysis of data. On the one hand, a set of interpretable features related to cell morphology allowed the identification of new potential targets or effectors in cancer cells through the appearance of discordant phenotypes with the rest of the population. On the other hand, machine learning algorithms capable of dealing with high dimensional and complex data allowed the identification of possible related genes based on concordant phenotypes in loss of function conditions.

The code for this project can be found [here](https://github.com/frodbej/tfm_madobis).
