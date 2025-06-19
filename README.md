# Hands-On Machine Learning with R (2e)

[![Status](https://img.shields.io/badge/status-work%20in%20progress-orange.svg)](https://github.com/bradleyboehmke/homl_2e)
[![License](https://img.shields.io/badge/license-TBD-lightgrey.svg)](./LICENSE)
[![Website](https://img.shields.io/badge/book-read%20online-brightgreen.svg)](https://koalaverse.github.io/homlr2/)

This is the public repository for the in-development second edition of **Hands-On Machine Learning with R** by Brad Boehmke and Brandon Greenwell.

> **Note: This is a Work in Progress**
>
> This book is being actively written and revised. The content is subject to significant changes, chapters may be incomplete, and code examples may be updated. We welcome feedback, but please be aware of the project's developmental nature.

---

## About the second edition

The goal of this second edition is to create a thoroughly modern, practical, and long-lasting guide to machine learning in R. Building on the foundation of the first edition, this version introduces several key enhancements:

* **A modern `tidymodels` core:** The book is now built entirely on the `tidymodels` framework, providing a cohesive, modular, and modern approach to the entire modeling workflow.
* **Focus on the full lifecycle:** We go beyond just training models to cover the end-to-end machine learning process, from feature engineering to production deployment and monitoring.
* **New, advanced topics:** To prepare you for the challenges of modern data science, we've added entirely new chapters on:
    * **MLOps:** Deploying, monitoring, and managing models in production.
    * **Ethical & responsible AI:** Understanding and auditing for bias, fairness, and transparency.
    * **Glass-box models:** Using powerful, inherently interpretable models like Explainable Boosting Machines (EBMs).
    * **Specialized domains:** Applying ML to time series, text, and survival analysis problems.
* **Engaging case studies:** We've replaced older datasets with fresh, modern case studies that are woven throughout the book, allowing you to apply concepts as you learn them.

This book is being written openly and will be freely available online. A print version is planned for publication with **CRC Press (Chapman & Hall/CRC Data Science Series)** upon completion.

## How to read the book

The latest rendered version of the book is always available to read online, thanks to [Quarto](https://quarto.org/) and GitHub Pages:

**[https://koalaverse.github.io/homlr2/](https://koalaverse.github.io/homlr2/)**

## Using this repository

This repository contains all the source code, data, and Quarto documents used to generate the book. We've designed it for maximum reproducibility.

### Reproducibility with `renv`

This project uses the `renv` package to ensure that you can use the exact same package versions that were used to write the book, guaranteeing that the code will always work as intended.

To get started:

1.  Clone or download this repository.
2.  Open the `homlr2.Rproj` file in RStudio.
3.  Run `renv::restore()` in the console. This will install all required packages at their correct versions into a project-specific library.

## Feedback and contributions

Your feedback is invaluable in helping us make this the best book possible. If you find typos, code errors, or have suggestions for clarification, please feel free to **[open a GitHub Issue](https://github.com/bradleyboehmke/homl_2e/issues)**.

At this time, we are not accepting direct pull requests for new content, but all suggestions in the Issues will be reviewed and considered.

## Authors

**Brad Boehmke** is a data scientist, educator, and author known for his work in making complex data science topics accessible.

**Brandon Greenwell** is a statistician and the author of several popular R packages for machine learning and model interpretability.

---

*The first edition of Hands-On Machine Learning with R can be found [here](https://www.routledge.com/Hands-On-Machine-Learning-with-R/Boehmke-Greenwell/p/book/9781138495685).*
