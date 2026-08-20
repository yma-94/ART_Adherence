# Large Language Model-Based Triage to Identify Antiretroviral Therapy Adherence Barriers and Risk Levels in Patient Messages

This repository contains the code and publicly shareable data associated with our study:

**Ma Y, Achiche S, Lessard D, et al. Large language model-based triage to identify antiretroviral therapy adherence barriers and risk levels in patient messages. JAMIA Open. 2026.**  
https://doi.org/10.1093/jamiaopen/ooag169

## Overview

We developed and evaluated large language model (LLM)-based classifiers to identify antiretroviral therapy (ART) adherence challenges from patient-generated text.

The study includes two sentence-level classification tasks:

- **Task I – Adherence barrier classification:** identification of seven ART adherence barrier domains, plus a `None` category.
- **Task II – Nonadherence risk classification:** stratification into `High`, `Medium`, `Low`, or `None` risk.

We compared fine-tuned general-domain and clinical language models with proprietary and open-source LLMs, and additionally evaluated model robustness to racial and gender descriptors and the environmental footprint of model development and inference.

## Demo

An interactive demonstration of the triage model is available on Hugging Face Spaces:

**[MARVIN Triage Model Demo](https://huggingface.co/spaces/marvin-cusm-chatbot/triage-model)**

The demo allows users to enter example patient messages and explore model predictions for ART adherence barriers and nonadherence risk levels.

## Data and code

This repository includes:

- Examples from the annotated dataset
- The complete synthetic dataset used for data augmentation
- A Jupyter notebook demonstrating the model training and fine-tuning workflow

The complete underlying dataset cannot be publicly released because it contains data derived from patient conversations, interviews, and community-submitted messages. Access to the full dataset may be requested from the corresponding author, subject to applicable privacy and ethics requirements.

## Citation

If you use the code or data from this repository, please cite:

Ma Y, Achiche S, Lessard D, et al. Large language model-based triage to identify antiretroviral therapy adherence barriers and risk levels in patient messages. *JAMIA Open*. 2026. doi:10.1093/jamiaopen/ooag169.

```bibtex
@article{ma2026triage,
  title   = {Large Language Model-Based Triage to Identify Antiretroviral Therapy Adherence Barriers and Risk Levels in Patient Messages},
  author  = {Ma, Yuanchao and Achiche, Sofiane and Lessard, David and others},
  journal = {JAMIA Open},
  year    = {2026},
  doi     = {10.1093/jamiaopen/ooag169}
}