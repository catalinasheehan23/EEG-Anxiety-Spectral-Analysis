# Resting-State EEG Spectral Power and Anxiety

This independent project explores relationships between resting-state EEG spectral power and trait anxiety (STAI) and behavioral inhibition (BIS) scores using Python and MNE-Python.

## Methods

Using publicly available EEG data from OpenNeuro, I analyzed alpha (9–14 Hz) and theta (4–8 Hz) spectral power during eyes-open and eyes-closed conditions.

I examined spectral power across the whole scalp, within frontal and parietal regions, and at individual electrodes. Pearson correlations and Benjamini–Hochberg false discovery rate (FDR) correction were used to investigate associations with anxiety and behavioral inhibition measures.

## Results

No statistically significant associations were identified after FDR correction.

## Dataset

[OpenNeuro — Resting-State EEG and Trait Anxiety](https://openneuro.org/datasets/ds007609)

## Notes

The analysis was conducted in Google Colab. The notebook references data stored in Google Drive, which are not included in this repository.
