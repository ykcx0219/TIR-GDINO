# TIR-GDINO

Official repository for the manuscript:

**Parameter-Efficient Adaptation of Grounding DINO for Thermal Infrared Object Detection**

## Status

This repository is currently under preparation.

The manuscript is under peer review. At this stage, the repository provides project information and will be progressively updated.

The complete implementation and reproduction instructions corresponding to the paper will be released upon acceptance/publication.

## Overview

TIR-GDINO is a parameter-efficient framework for adapting Grounding DINO to thermal infrared object detection while preserving its pre-trained vision-language grounding capability.

The framework contains four main components:

- Dual-path Thermal Low-Rank Adaptation (DT-LoRA)
- Thermal Feature Calibration (TFC)
- Attribute-enriched Prompting (Attr-Prompt)
- Prompt-guided Query Allocation (PQA)

## Base Model

This work is built upon Grounding DINO.

Base repository:

`https://github.com/IDEA-Research/GroundingDINO`

The exact upstream version used in our experiments will be specified in the reproducible release.

## Datasets

Experiments are conducted on:

- FLIR ADAS v2
- LLVIP
- IR-Det

FLIR ADAS v2 and LLVIP are publicly available from their official sources.

IR-Det is not publicly distributed because it contains images of human participants and is subject to privacy and consent restrictions.

## Code Availability

The repository is currently a pre-release project page.

A complete reproducible release, including the implementation of the proposed modules, training configurations, evaluation scripts, and reproduction instructions, will be provided upon acceptance/publication.

## Citation

Citation information will be added after publication.
