# Surgical Scene Segmentation in Robotic Gastrectomy Dataset

This repository contains the dataset and related resources for the MICCAI 2022 paper "Surgical Scene Segmentation in Robotic Gastrectomy" [1].

## Overview

The dataset combines real and synthetic data for surgical scene segmentation in robotic gastrectomy procedures. It includes:

- Real surgical video frames from 40 cases of distal gastrectomy for gastric cancer performed with the da Vinci Surgical System (dVSS).
- A virtual surgery environment created using Unity, featuring five organs and 22 surgical instruments.
- Synthetically generated images using semantic image synthesis techniques.

## Contents

### Data Structure

The dataset is organized into the following directories:

- `images`: Contains the raw images
- `instance_jsons`: JSON files with instance-level annotations
- `raw_syn_masks`: Raw segmentation masks for synthetic images
- `semantic_masks`: Semantic segmentation masks
- `category.json`: Class information file
- `info.txt`: Dataset metadata

### Data Types

1. Real Data (R): Annotated surgical video frames from real procedures
2. Manual Synthetic Data (MS): Manually generated virtual surgery scenes
3. Domain Randomized Synthetic Data (DRS): Automatically generated virtual surgery scenes using domain randomization

## Usage

To use this dataset, follow these steps:
2. Extract the contents to your desired directory
3. Refer to the provided scripts for data exploration and analysis



## Contact



[Last updated: YYYY-MM-DD]
