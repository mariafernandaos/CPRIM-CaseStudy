# CPRIM Study Case in a Photovoltaic Generation Systems

## What is CPRIM

CPRIM is a novel approach for identifying risks related to Industry 4.0 assets, considering mainly technical and operational aspects. It combines various standards, methods, and guidelines from academia and industry. It evaluates industrial assets as elements of a Cyber-Physical System (CPS) and identifies cyber-physical risks in a layer-oriented approach. CPRIM defines assets as systems, subsystems, equipment, and components relevant to risk identification. The approach follows a classical three-layer CPS model, identifying risks in the physical, cyber, and cyber-physical layers.

To ensure comprehensive coverage, CPRIM employs three separate risk identification processes. The first process utilizes ISO 31000/2018 and Risk Model to diagnose risk factors in the CPS layers. The second process involves the bottom-up application of HAZOP to identify risks in the physical layer and extend its analysis to the cyber-physical layer. Using a top-down strategy, the third process applies NIST CSF to identify risks starting in the cyber layer and extending into the cyber-physical layer.

## About this repository

This repository contains complementary artifacts from a CPRIM study case in a Photovoltaic (PV) generation system, described in detail in the referenced paper. The following artifacts include the complete lists of risks resulting in each CPRIM's phase:

* [Risk list - After P2](Risk%20list%20-%20After%20P2.pdf) reports the complete list of risks obtained after P-2 (i.e., risk factor diagnostics, bottom-up HAZOP, and top-down NCSF processes). It contains 144 risks described adequately with their respective events, causes, and consequences.
* [Risk list - Without redundancies](Risk%20list%20-%20Without%20redundancies.pdf) presents the resulting list of risks after removing redundancies (i.e., P-3 Redundancy Elimination). It contains 124 risks which constitute a subset of the previous list;
* [Risk list - After aggregation](Risk%20list%20-%20After%20agreggation.pdf) shows the consolidated list of risks after the aggregation step (i.e., P-3 Risk Aggregation). It contains 108 risks that are the final CPRIM's outcome in practice.
* [NCSF - Subcategories](NCSF%20-%20Subcategories.pdf) contains complementary information about the top-down NSCF risk identification process (i.e., the NIST Cyber Security Framework application). It describes the selected subcategories in the NCSF's Identification function and the respective risks related to each.
