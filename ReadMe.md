#Disclaimer
This code is a proof of concept and part of an ongoing work. It is provided for reproducing the results of a published paper.
__This code is NOT intented for production use__

# ANR Vision-3E: Paper Eusipco 2024
This repository contains the code to reproduce the results of the paper;
"Prédiction des instants de changement de percept dans un modèle de perception mutlistable"
Submitted to the conference Gretsi 2025


# Aknowlegement
This work was supported by NeuroCoG IDEX UGA, “Investissements d'avenir” program [grant number ANR-15-IDEX-02] and by the project VISION-3E [grant number ANR-21-CE37-0018]

# Code structure
The code is groupd in a single jupyter notebook __Code_paper_Gretsi2025_Bayesian_Modeling_of_percept_Change__

Running the notebook will:
  - Run the simualtion of the model of Huguet et al. [5]
  - Extract the domiance times of the perceptual sequence
  - Fit distributions to the dominance times
  - Fit a model on the distribution of the input firing rates difference $\Delta I$ conditional to the time to percept switch $D$
  - Generate the posterior distribution of the time to change of percept given $\Delta I$
  - Display this distribution on a short simulation of the model
  - Save all the figures presented in the paper






