# AlphaFold3 vs ESMFold and OmegaFold: Benchmark Data

## Description
This repository contains supplementary data for the article:

**"AlphaFold3 Compared to ESMFold and OmegaFold: Defining Performance Boundaries for Protein Structure Prediction"**

Authors: Jade Lascoux¹ and Anuar Badrul²

¹ Faculty of Computer Science and Information Technology, University of Malaya, Malaysia  
² CESI Engineering School, Toulouse, France

## Abstract
Systematic comparison of AlphaFold3, ESMFold, and OmegaFold across 14 proteins representing key structural prediction challenges: monomers with varying MSA availability, multi-chain assemblies, orphan proteins, and intrinsically disordered proteins (IDPs).

## Repository Contents

### Data Files
| File | Description |
|------|-------------|
| `data/Table_S1_Protein_Dataset.xlsx` | Complete protein dataset characteristics (PDB IDs, chain information, MSA depth, structural properties) |
| `data/Table_S2_Prediction_Results.xlsx` | Detailed prediction results for all models (RMSD, pLDDT, PTM, iPTM, runtime, disorder fractions) |

### Key Findings
- **AlphaFold3**: 80% best accuracy on monomers with MSA, but 71% failure rate on multi-chain assemblies
- **ESMFold**: Zero catastrophic failures, appropriate confidence calibration for IDPs, 57-850× faster than AlphaFold3
- **OmegaFold**: Competitive performance on structured proteins, calibration issues for disorder prediction

## How to Use
1. Download the Excel files from the `data/` folder
2. Each file contains multiple sheets with detailed metrics
3. Data can be used for further analysis or validation

## Citation
If you use this data, please cite:
```
Lascoux, J. & Badrul, A. (2025). AlphaFold3 Compared to ESMFold and OmegaFold: 
Defining Performance Boundaries for Protein Structure Prediction.
```

## License
This data is released under the [CC-BY-4.0 License](https://creativecommons.org/licenses/by/4.0/).

## Contact
For questions or additional data requests, please contact:
- Jade Lascoux: jade.lascoux@viacesi.fr
