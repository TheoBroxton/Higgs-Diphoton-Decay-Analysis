# Higgs Diphoton Decay Analysis

This repository contains a small selection of the work done for the third year particle physics lab in 2024 at the University of Manchester, analysing the diphoton decay of the Higgs boson. The analysis was performed using the ROOT framework and the 13TeV open data set from ATLAS at the LHC. Supervision was provided by Prof. Terry Wyatt FRS and Prof. Alex Oh, with very high praise received for the overall work, presentation and interview. 

Whilst there was plenty of code involved in the analysis, I have chosen to omit uploading the full codebase. This is because the basic framework was written by those who developed the lab and I do not wish to take credit for their work or share it without their permission. Whilst there is of course code - solely my own - I could upload, I do not feel it would be particularly useful in isolation.

Instead, I have chosen to upload the presentation slides, report, and a selection of figures and my own data from analysis.

## Presentation

The presentation slides, `Presentation.pdf`, were presented to the supervising professors at the end of the lab. Naturally as only part of the presentation (the other part being oral), the slides are not self-contained. I hope that they are still useful in isolation, however. They aim to motivate the concept of 'finding the Higgs boson' using invariant mass distributions and the necessity of appropriate selection cuts and background modelling. An outline of the methodology is given for this, as well as for the calculation of cross sections and importantly, the estimation of uncertainties. In the appendices, additional plots, analysis and information is given to aid potential explanations to the professors' questions.

## Report

The lab report, `Report.pdf`, is a more detailed account of the work done. It includes the methodology, results, and discussion of the analysis. This report provides a brief overiew of the analysis in the format of a scientific paper, however as it was constrained to a length of 3 pages, the **vast majority** of the work is unfortunately omitted. It is intended to be a concise summary of the work done, and it is hoped that it will provide a useful overview of the analysis.

## Figures and Data

The figures and data files are provided in the `Figures/` and `Data/` directories respectively. The figures include many histograms produced using ROOT:

- Plots of various parameters of interest (e.g. invariant mass, transverse momentum[0,1], pseudorapidity[0,1,mean], et/ptcone[0,1], etc.) for each separate selection cut imposed
- Fits for various functional forms to model the background in the diphoton invariant mass distribution
- Background subtraction as an attempt to isolate signal events
- Signal fitting of the MC simulated Higgs boson peak in the invariant mass distribution
- Combined background and signal fits to the invariant mass distribution
- Cross section histograms from rerunning cross section analysis with various changes to estimate systematic uncertainty (also againt et/ptcone to ensure a non-trivial relationship, i.e. that they contribute to the systematic uncertainty)

Note that a distinction should be made between the histograms produced using the Monte Carlo (MC) simulated data and those produced using the real data.

The data files included are simply some of the records I kept during the analysis, where I was altering and iterating selection cuts, background fits and cross section calculations.
