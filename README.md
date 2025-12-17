# toros-menalla-freshwater-ecosystems

## Context

This repository provides the R codes and datasets used for the analyses and figures presented in the manuscript: **"Reconstructing the freshwater paleoecosystems diversity of Toros-Menalla (Late Miocene, Chad) from an integrated faunal perspective"** by Axelle Gardin, Olga Otero, Géraldine Garcia, Clarisse Nekoulnang, Fabrice Lihoreau, Abderamane Moussa, Mathieu Schuster, Lorenzo Scribano, & Franck Guy.

***This repository is licensed under the CC BY 4.0 License. You are free to use, share, and adapt the materials, provided that proper attribution is given.***

This work focuses on reconstructing Late Miocene freshwater habitat at Toros-Menalla (northern Chad Basin), where aquatic and terrestrial ecosystems were tightly interconnected. While terrestrial vertebrate assemblages have been extensively studied, aquatic habitats have remained poorly resolved.

By integrating data from five Toros-Menalla sites (including fossil freshwater-dwelling vertebrate assemblages, and discussion with depositional contexts, stable isotopes, and field observations) this study highlights a complex network of freshwater habitats, ranging from floodplains and swamps to open waterbodies with currents. Most assemblages represent spatial habitat diversity rather than temporal succession, with the exception of TM266, which may reflect vertical mixing. The Bol Archipelago (Lake Chad) may be a coherent modern analogue for illustrating Toros-Menalla ecosystem dynamics and site formation. This work emphasizes the importance of systematic, grid-based fossil collection and sieving to capture representative aquatic biodiversity and reconstruct paleoecosystems with ecological precision.

This script is provided as supplementary information and will be publicly released upon publication.

## Folder organisation

-   `data/`: datasets including:
    -   `TM_Aquatic_Abundance.csv` – contains abundance data for freshwater-dwelling taxa in the five studied sites (TM90, TM242, TM252, TM266, TM337), including **Number of Specimens** and **Minimum Number of Individuals** (**MNI)**;
    -   `TM_AquaticTerrestrial_Proportions.csv` – contains proportions of aquatic and terrestrial vertebrate groups used to build comparative pie charts.
-   `figures/`: generated figures with the script (rarefaction curves, clustering, etc.);
-   `README.md`: this file;
-   `TM_freshwater_ecosystems.qmd`: script for running the analyses and build the figures presented in the manuscript.
