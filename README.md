# Docking results for DNMT1 
[![Powered by RDKit](https://img.shields.io/badge/Powered%20by-RDKit-3838ff.svg?logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAAQBAMAAADt3eJSAAAABGdBTUEAALGPC/xhBQAAACBjSFJNAAB6JgAAgIQAAPoAAACA6AAAdTAAAOpgAAA6mAAAF3CculE8AAAAFVBMVEXc3NwUFP8UPP9kZP+MjP+0tP////9ZXZotAAAAAXRSTlMAQObYZgAAAAFiS0dEBmFmuH0AAAAHdElNRQfmAwsPGi+MyC9RAAAAQElEQVQI12NgQABGQUEBMENISUkRLKBsbGwEEhIyBgJFsICLC0iIUdnExcUZwnANQWfApKCK4doRBsKtQFgKAQC5Ww1JEHSEkAAAACV0RVh0ZGF0ZTpjcmVhdGUAMjAyMi0wMy0xMVQxNToyNjo0NyswMDowMDzr2J4AAAAldEVYdGRhdGU6bW9kaWZ5ADIwMjItMDMtMTFUMTU6MjY6NDcrMDA6MDBNtmAiAAAAAElFTkSuQmCC)](https://www.rdkit.org/)
    
The initial dataset was retrieved from ChEMBL API v.32, compounds with unequivocally assigned IC50 were selected and saved in the file "ChEMBL32_DNMT1_196.csv". <br>
Compounds with nucleoside scaffolds were removed with the script "Scaffolds_Nucleoside_analogs.ipynb". Docking scores calculated for the 153 ligands with DNMT1 (PDB ID: 4WXX) using AutoDock Vina (Scores_Vina), LeDock (Scores_Ledock), and MOE (Scores_MOE) software were added to the file "Docking_DNMT1_153.csv". The analysis of the results was carried out with the script "Docking_results_analysis.ipynb".

![Figure](https://github.com/DIFACQUIM/DNMT1-Protocol/blob/1207c017cf0046abc69f4728fca77e16c9f9b13b/Figure.jpg)

#### References

Please, cite our paper:

Prado-Romero DL, Gómez-García A, Cedillo-González R, Villegas-Quintero H, Avellaneda-Tamayo JF, López-López E, Saldívar-González FI, Chávez-Hernández AL and Medina-Franco JL (2023) Consensus docking aid to model the activity of an inhibitor of DNA methyltransferase 1 inspired by de novo design. Front. Drug Discov. 3:1261094. doi: [10.3389/fddsv.2023.1261094](https://www.frontiersin.org/articles/10.3389/fddsv.2023.1261094/full)
