# Rifampicin PBPK-PD model for tuberculosis (MTP framework)

Code and model files accompanying the manuscript *[title to be added]* (Garamani et al., [journal and status to be added]).

The repository contains a whole-body physiologically based pharmacokinetic (PBPK) model of rifampicin, built in PK-Sim and MoBi (Open Systems Pharmacology Suite), coupled to the multistate tuberculosis pharmacometric (MTP) model of Clewe et al. (2016). The MTP model is implemented in MoBi and linked directly to the PK-Sim rifampicin model.

## Data and code availability

The MoBi implementation of the MTP model, the R code for PBPK–PD coupling and post-processing, and the digitised controlled-release dissolution profiles used for the modified-release formulation simulations (Hiremath and Saha, 2008) are available at https://github.com/DylanGaramani/rifampicin-pbpk-pd-tb.

The rifampicin PBPK model is the rifampicin model from the Open Systems Pharmacology PBPK Model Library (version 2.0, OSP Suite 12.3), available at https://github.com/Open-Systems-Pharmacology/OSP-PBPK-Model-Library (release v12.3).

Observed clinical data used for comparison are taken from published studies (te Brake et al., 2021; Svensson et al., 2018).

## Contents

- **MTP model (MoBi):** the multistate tuberculosis model implemented in MoBi, coupled to the PK-Sim rifampicin model.
- **R code:** scripts for PBPK–PD coupling, simulations and post-processing, using `ospsuite`.
- **Dissolution data:** digitised controlled-release dissolution profiles used for the modified-release formulation simulations.
- **Reproduction script:** code reproducing the in vitro bactericidal dynamics of Clewe et al. (2016), Figure 3.

## Requirements

- OSP Suite 12.3 (PK-Sim and MoBi)
- R with `ospsuite`, `ggplot2`, `dplyr` and `patchwork`

## Reproducing the results

Step-by-step instructions will be added once all files are uploaded.

## Citation

Garamani D. et al. *[title, journal and DOI to be added]*.

## License

[To be added.]

## Contact

Please open an issue in this repository.
