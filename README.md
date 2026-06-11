# PhiID Motor Learning Derived Data

This repository contains de-identified derived data supporting the manuscript:

**Learning a novel visuomotor task leads to reorganization of information dynamics toward synergistic transfer in resting-state brain networks**

The study examined learning-related changes in resting-state fMRI information dynamics before and after a seven-session visuomotor foot-drawing training protocol. Integrated Information Decomposition (ΦID) was used to quantify redundancy- and synergy-related information dynamics across whole-brain ROI pairs.

## Repository purpose

This repository is intended to provide derived result tables that support the main findings, supplementary analyses, and statistical summaries reported in the manuscript. It does **not** contain raw participant-level MRI data or analysis code.

Raw participant-level MRI data are not publicly available because of institutional ethics and data-use restrictions. Analysis code is not publicly available but may be requested from the corresponding author.

## Repository structure

```text
Data/
├── atom_level/
├── global/
├── network_edge/
└── tau_sensitivity/
```

## Folder descriptions

### `Data/global/`

This folder contains participant-level and group-level derived summaries for the main global ΦID outcomes, including:

* global synergistic transfer (`str`)
* redundancy transfer (`rtr`)
* synergy-minus-redundancy balance (`str − rtr`)
* primary and secondary paired statistical tests
* effect sizes
* bootstrap and permutation validation
* multiple-comparison summaries
* sensitivity analysis excluding the high-motion participant

These files support the main global results and the primary/secondary statistical summaries reported in the manuscript.

### `Data/atom_level/`

This folder contains the 16-atom ΦID specificity analysis.

Included files summarize:

* statistics for all 16 ΦID atoms
* subject-level pre-training, post-training, and post–pre change values
* atom-level effect sizes and corrected statistical summaries

These files support Supplementary Table S4 and the atom-level specificity results.

### `Data/network_edge/`

This folder contains derived edge-level and network-level summaries for post-training changes in synergistic transfer.

Included files summarize:

* edge-level post–pre changes in synergistic transfer
* top-ranked positive edges
* permutation-based edge summaries
* ROI annotations used for network/edge interpretation
* network-pair summaries of learning-related Δstr effects

These files support the spatial and network-level interpretation of the main ΦID findings.

### `Data/tau_sensitivity/`

This folder contains sensitivity analyses evaluating whether the main global ΦID findings are robust across temporal lags.

Included files summarize results for:

* tau = 1
* tau = 2
* tau = 3

These files support the lag-sensitivity analyses reported in the supplementary material.

## Data availability

The raw participant-level MRI data are not publicly available because of institutional ethics and data-use restrictions. De-identified derived data supporting the main findings of this study, including participant-level global ΦID measures, primary and secondary statistical summaries, atom-level summaries, edge-level synergistic-transfer results, and tau-sensitivity analyses, are provided in this repository.

Analysis code is not publicly available but is available from the corresponding author upon reasonable request. Methodological details and derived outputs needed to verify the reported results are provided in the manuscript, supplementary material, and this repository.

## Files not included

This repository does not include:

* raw MRI data
* preprocessed participant-level MRI images
* raw ROI time series
* full participant-level neuroimaging files
* analysis scripts/code
* protected or identifiable participant-level source data

These files are excluded because of institutional ethics restrictions, data-use limitations, or project-specific code dependencies.

## Citation

If you use or refer to these derived data, please cite the associated manuscript:

Rezaei, M., Talesh Jafadideh, A., Bahrami, F., & Tahmasebi Boroujeni, S.
**Learning a novel visuomotor task leads to reorganization of information dynamics toward synergistic transfer in resting-state brain networks.**

Citation details will be updated after publication.

## Contact

For questions about the derived data or requests regarding analysis code, please contact the corresponding author:

**Fariba Bahrami**
Human Motor Control and Computational Neuroscience Laboratory
School of Electrical and Computer Engineering
College of Engineering, University of Tehran
Email: [fbahrami@ut.ac.ir](mailto:fbahrami@ut.ac.ir)
