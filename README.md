# toros-menalla-freshwater-ecosystems

## Context

This repository provides the R codes and datasets used for the analyses and figures presented in the manuscript: **"Reconstructing the freshwater paleoecosystem diversity of Toros-Menalla (Late Miocene, Chad) from an integrated faunal perspective"** by Axelle Gardin, Olga Otero, Géraldine Garcia, Clarisse Nekoulnang, Fabrice Lihoreau, Abderamane Moussa, Mathieu Schuster, Lorenzo Scribano, & Franck Guy.

This work focuses on reconstructing Late Miocene freshwater habitat at Toros-Menalla (northern Chad Basin), where aquatic and terrestrial ecosystems were tightly interconnected. While terrestrial vertebrate assemblages have been extensively studied, aquatic habitats have remained poorly resolved.

By integrating data from five Toros-Menalla sites (including fossil freshwater-dwelling vertebrate assemblages, and discussion with depositional contexts, stable isotopes, and field observations) this study highlights a complex network of freshwater habitats, ranging from floodplains and swamps to open waterbodies with currents. Most assemblages represent spatial habitat diversity rather than temporal succession, with the exception of TM266, which may reflect vertical mixing. The Bol Archipelago (Lake Chad) may be a coherent modern analogue for illustrating Toros-Menalla ecosystem dynamics and site formation. This work emphasizes the importance of systematic, grid-based fossil collection and sieving to capture representative aquatic biodiversity and reconstruct paleoecosystems with ecological precision.

This script is provided as supplementary information and will be publicly released upon publication.

## Folder organisation

-   `data/`:
    -   `TM_Aquatic_NISP_MNI.csv` – contains abundance data for freshwater-dwelling taxa in the five studied sites (TM90, TM242, TM252, TM266, TM337), including **Number of Identifierd Specimens (NIPS)** and **Minimum Number of Individuals** (**MNI)**;
    -   `TM_aquatic_terrestrial_proportion.csv` – contains proportions of aquatic and terrestrial vertebrate groups used to build comparative pie charts.
    -   `TM_taxon_ecological_matrix.csv` – contains ecological categories (habitat association and ecological tolerance) associated to each taxon, according to Table 1 of the main text.
-   `figures/`: generated figures with the script (rarefaction curves, clustering, etc.);
-   `results/`: generated dataframes, including the standardised taxonomic ranks of abundance and Tables S1 to S4 on MNI sensitivity tests.
-   `README.md`: this file;
-   `TM_freshwater_ecosystems.qmd`: script for running the analyses and build the figures presented in the main text and supplementary information.

## Citation

***This repository is licensed under the CC BY 4.0 License.*** If you use the data, code, or figures from this repository in your work, please cite it as:

Axelle Gardin, Olga Otero, Géraldine Garcia, Clarisse Nekoulnang, Fabrice Lihoreau, Abderamane Moussa, Mathieu Schuster, Lorenzo Scribano, & Franck Guy (2026). *Toros-Menalla Freshwater Ecosystems*. GitHub repository. <https://doi.org/10.5281/zenodo.17963310>
