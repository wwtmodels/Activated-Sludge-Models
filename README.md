# Activated-Sludge-Models

This repository contains the different Activated Sludge Models implementations developed between [Lund University](https://www.iea.lth.se/) and the [Technical University of Denmark](https://www.kt.dtu.dk/english/research/prosys).

<strong>1. ASM1, 2d and 3 implemented in BSM1 </strong>  

This implementation of ASM1, 2d and 3 account implemented in the BSM1 layout accounts for 1) reactive settling and 2) electron dependency. The Main developers are: [Xavier Flores-Alsina](https://github.com/xfalsina), [Krist V. Gernaey](https://github.com/kristgernaey), and [Ulf Jeppsson](https://github.com/ulfjeppsson). The model is described in the following paper: 

[Flores-Alsina X., Gernaey K.V. and Jeppsson, U. (2012). Benchmarking biological nutrient removal in wastewater treatment plants: influence of mathematical model assumptions. Water Sci. Technol., 65 (8): 1496-1505](https://doi.org/10.2166/wst.2012.039). 

This version of the model is adapted to be run in Matlab 2019b (or newer).

[![ADM](https://img.shields.io/badge/DOWNLOAD%20ASM1%202d%203%20in%20BSM1-990000?style=for-the-badge)](https://github.com/wwtmodels/Activated-Sludge-Models/releases/download/v1/ASM1.2d.3.in.BSM1.zip) [![](https://img.shields.io/github/downloads/wwtmodels/Activated-Sludge-Models/v1/total?color=990000&label=Downloads&style=for-the-badge)](https://github.com/wwtmodels/Activated-Sludge-Models) 

<strong>2. ASM1, 2d and 3 implemented in BSM1 (with pH calculations) </strong> 

The previous implementation is upgraded with aqueous phase chemistry models accounting for 1) ion pairing and 2) activity corrections. The latter allows you to predict weak-acid base conditions and therefor pH. The main developers are: [Xavier Flores-Alsina](https://github.com/xfalsina), Christian Kazadi Mbamba, [Kimberly Solon](https://github.com/KimberlySolon), Darko Vrecko, Stephan Tait, [Damien J Batstone](https://github.com/damienbatstone), [Ulf Jeppsson](https://github.com/ulfjeppsson), [Krist V. Gernaey](https://github.com/kristgernaey). The model is described in the following paper: 

[Flores-Alsina X, Kazadi-Mbama C., Solon K., Vrecko D., Tait S., Batstone D., Jeppsson U. and Gernaey K.V. (2015). A plant wide aqueous phase chemistry module describing pH variations and ion speciation/pairing in wastewater treatment models. Water Research, 85, 255-265](https://doi.org/10.1016/j.watres.2015.07.014). 

This version of the model is adapted to be run in Matlab 2019b (or newer).

[![ADM](https://img.shields.io/badge/DOWNLOAD%20ASM1%202d%203%20in%20BSM1%20with%20pH-990000?style=for-the-badge)](https://github.com/wwtmodels/Activated-Sludge-Models/releases/download/v3/ASM1.2d.3.pH.zip) [![](https://img.shields.io/github/downloads/wwtmodels/Activated-Sludge-Models/v2/total?color=990000&label=Downloads&style=for-the-badge)](https://github.com/wwtmodels/Activated-Sludge-Models) 

<strong>3. ASM2d implemented in an industrial bio-reactor (with N2O emissions) </strong>

The process kinetics and stoichiometry are adapted from the Activated Sludge Model No. 2d (ASM2d). The original mathematical structure was modified to incorporate ammonium oxidizing bacteria (AOB) inhibition by NO2−. To comprehensively capture N2O production, the model includes three biological N2O production pathways: 1) Nitrifier nitrification pathway (NN pathway), 2) Nitrifier denitrification pathway (ND pathway) and 3) Heterotrophic denitrification pathway (DEN pathway). The gas-liquid (G-L) transfer processes, are modeled differently across 1) anoxic and 2) aerobic stages. The Main developers are: The Main developers are: , and [Tianyu Lei](https://github.com/constianlei),  [Xavier Flores-Alsina](https://github.com/xfalsina), [Krist V. Gernaey](https://github.com/kristgernaey). The model is described in the following paper: 

[Lei, T., Whale-Obrero, J., Larsen, S. B., Kjellberg, K., Gernaey, K. V., & Flores-Alsina, X. (2025). Dynamically predicting nitrous oxide emissions in a full-scale industrial activated sludge reactor under multiple aeration patterns and COD/N ratios. Water Research. 123379](https://doi.org/10.1016/j.watres.2025.123379). 

[![ADM](https://img.shields.io/badge/DOWNLOAD%20ASM2d%20with%20N2O-990000?style=for-the-badge)](https://github.com/wwtmodels/Activated-Sludge-Models/releases/download/v3/ASM2d_N2O_pHadjust.zip) [![](https://img.shields.io/github/downloads/wwtmodels/Activated-Sludge-Models/v3/total?color=990000&label=Downloads&style=for-the-badge)](https://github.com/wwtmodels/Activated-Sludge-Models) 

This version of the model is adapted to be run in Matlab 2022b (or newer).

![logo](WWTMlogo.png)
