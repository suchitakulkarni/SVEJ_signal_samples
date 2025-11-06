The repository corresponds to model presented in arXiv:2511.02918.
Pythia version 8.312. 
The repository contains two folders 
1) A pythia card for simulating SVEJ signal without madgraph in directory Pythia_cards_no_mg5
2) A sample events for three different lambda values as generated using MadGraph + Pythia setup in Pythia_plus_mg5_setup

It is recommended to start from the Pythia_cards_no_mg5 to check how the signal looks like and later on move to setup with MadGraph.

MadGraph matching, merging should be carefully checked. 
For running MadGraph generated samples using existing pythia cards, either remove the hadronization parameters in the pythia cards i.e. run with the wrong hadronization parameters or modify pythia xml file (instructions will be updated here)

   
