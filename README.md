# A Mechanistic PBPK-PD Framework to Predict Early Bactericidal Activity of Rifampicin

Code and model files accompanying the manuscript *A Mechanistic PBPK-PD Framework to Predict Early Bactericidal Activity of Rifampicin Across Populations, Formulations and Adherence Scenarios: A Proof-of-Concept Study* by Dylan Garamani, Albert Mihranyan and Erik Sjögren (Department of Pharmaceutical Biosciences, Uppsala University). [Journal, volume and DOI to be added.]

The repository contains a whole-body physiologically based pharmacokinetic (PBPK) model of rifampicin, built in PK-Sim and MoBi (Open Systems Pharmacology Suite), coupled to the multistate tuberculosis pharmacometric (MTP) model of Clewe et al. (2016). The MTP model is implemented in MoBi and linked directly to the PK-Sim rifampicin model.

## Data and code availability

The MoBi implementation of the multistate tuberculosis pharmacometric (MTP) model, the R code for PBPK–PD coupling and post-processing, and the digitised in vitro dissolution datasets used for the modified-release formulation simulations are available at https://github.com/DylanGaramani/rifampicin-pbpk-pd-tb. The dissolution profiles were digitised from the figures of Hiremath and Saha (2008) and extrapolated to 100% cumulative release.

The underlying rifampicin PBPK model is publicly available from the Open Systems Pharmacology PBPK Model Library, Rifampicin folder, at commit 07a71b3e025879db5cc46feca1d262cc786ed0f6: https://github.com/Open-Systems-Pharmacology/OSP-PBPK-Model-Library/tree/07a71b3e025879db5cc46feca1d262cc786ed0f6/Rifampicin

Observed clinical data used for comparison are taken from published studies (te Brake et al., 2021; Svensson et al., 2018). These clinical data are not included in this repository.

## Contents

- **MTP model (MoBi):** the multistate tuberculosis model implemented in MoBi, coupled to the PK-Sim rifampicin model.
- **R code:** scripts for PBPK–PD coupling, simulations and post-processing, using `ospsuite`.
- **Dissolution data:** digitised in vitro release profiles of the modified-release rifampicin formulations (Hiremath and Saha, 2008), extrapolated to 100% release.
- **Reproduction script:** code reproducing the in vitro bactericidal dynamics of Clewe et al. (2016), Figure 3.

## Requirements

- PK-Sim and MoBi (OSP Suite v12)
- R v4.5.0 with `ospsuite` v12.4.3 and the tidyverse packages

## Citation

[To be added.]

## License

[To be added.]

## Contact

Please open an issue in this repository.
