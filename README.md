# [Miss_Teng](https://doi.org/10.5281/zenodo.19673299)

https://doi.org/10.5281/zenodo.19673299

**Miss_Teng** is an artificially constructed MSI-like dataset created for engineering-level testing and workflow demonstration of the R package **ARBO**.

## Overview

This repository provides a large MSI-like example dataset in imzML format for evaluating the computational handling of large inputs in ARBO.

The dataset has the following characteristics:

- **1,000 features**
- **1,572,864 spectra / pixels**
- **Spatial dimensions:** 1024 × 1536
- **Mass range:** 50–1500
- **Centroided:** FALSE

## Origin of the dataset

**Miss_Teng** was not generated from a real mass spectrometry imaging experiment.

Instead, it was artificially constructed using a portrait-style image as a visual template. The image was derived from the author's own portrait and further transformed using AI-assisted image generation/stylization. The final image is a stylized animated portrait resembling a young woman, but it does **not** depict a real female participant.

The image was used only as the visual basis for constructing this MSI-like dataset.

## Intended use

**Miss_Teng** was created primarily to test the processing capability of **ARBO** on large MSI-like data. It can be used for software-level and workflow-level testing, including:

- imzML data handling
- spectra matrix extraction
- preprocessing
- dimensionality reduction
- clustering
- spatial visualization
- workflow demonstration
- scalability-oriented testing

This dataset should therefore be understood as an **engineering test case** or **scalability-oriented example**, rather than a biological or analytical benchmark dataset.

## Limitations

The **m/z values**, **spectral patterns**, and **spatial signal structures** in this dataset do **not** carry real biochemical, pathological, or experimental meaning.

Accordingly, this dataset is **not suitable** for:

- biological interpretation
- metabolite annotation
- scientific inference
- serious analytical validation
- formal benchmark comparisons between MSI methods

Please do not use this dataset as a formal benchmark dataset for methodological comparison in scientific publications.

## Repository contents

This repository may include:

- the **Miss_Teng** imzML-based dataset
- the portrait-style source image used as a construction template
- HTML files showing ARBO-based processing workflows and analysis results

The HTML files document example analyses of this dataset using **ARBO**, including processing steps and visualization results.

## Image usage note

The portrait-style image included in this repository is provided only to help document and understand the origin of the synthetic dataset construction.

The image is a synthetic, AI-transformed derivative of the author's own portrait. It is **not** a real MSI sample image, **not** a biological reference image, and **not** a ground-truth annotation.

The image is included for documentation purposes only. Reuse, redistribution, or use of the image outside the context of this repository is **not recommended without permission from the author**.

## Disclaimer

**Miss_Teng** is a synthetic MSI-like dataset constructed solely for software testing, workflow demonstration, and scalability evaluation. It is not a real experimental MSI dataset and should not be used for biological interpretation or formal scientific benchmarking.
