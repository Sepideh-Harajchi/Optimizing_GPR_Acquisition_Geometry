# Optimizing_GPR_Acquisition_Geometry

The repository contains the processed datasets, supporting files, and documentation required to facilitate reproducibility and verification of the reported results.

---

## Associated publication

This repository accompanies the manuscript:

**Optimizing GPR acquisition geometry for automated railway embankment and supporting-soil assessment**

submitted to the *Transportation Geotechnics*.

---

## Author

Sepideh Harajchi  
Department of Geoscience and Engineering  
Delft University of Technology, The Netherlands  

---

## Contact

- [s.harajchi@tudelft.nl](mailto:s.harajchi@tudelft.nl)  
- [sepideh.harajchii@gmail.com](mailto:sepideh.harajchii@gmail.com)  

---

## Repository structure


### 00_GPR_Survey

This folder contains supporting information describing the study site, GPR survey configuration, and overall experimental workflow.

- **Figure 1:** Location of the study site along the Delft–Schiedam railway corridor in Schiedam, the Netherlands, including the approximately 200 m investigated railway section.
- **Figure 2:** Survey layout showing the seven longitudinal GPR profile groups (G1–G7), railway tracks, boreholes, and CPT locations.
- **Figure 3:** GPR acquisition system used during the field survey, consisting of a GSSI SIR-4000 control unit and a 400 MHz shielded antenna mounted on an adjustable survey trolley.
- **Figure 4:** Overview of the workflow used for GPR acquisition, preprocessing, attribute extraction, and geotechnical validation.

The GPR survey comprised 21 longitudinal profiles (7 survey groups × 3 antenna clearances) acquired at nominal antenna clearances of **0, 10, and 40 cm**.

#### Survey figures

<p align="center">
  <img src="00_GPR_Survey/Fig1.png" width="850" alt="Figure 1 - Study site location">
</p>

<p align="center"><em>Figure 1. Location of the study site along the Delft–Schiedam railway corridor in Schiedam, the Netherlands, including the approximately 200 m investigated railway section.</em></p>

<p align="center">
  <img src="00_GPR_Survey/Fig2.png" width="850" alt="Figure 2 - GPR survey layout">
</p>

<p align="center"><em>Figure 2. Survey layout showing the seven longitudinal GPR profile groups (G1–G7), railway tracks, boreholes, and CPT locations.</em></p>

<p align="center">
  <img src="00_GPR_Survey/Fig3.png" width="750" alt="Figure 3 - GPR acquisition system">
</p>

<p align="center"><em>Figure 3. GPR acquisition system used during the field survey.</em></p>

<p align="center">
  <img src="00_GPR_Survey/Fig4.png" width="850" alt="Figure 4 - GPR workflow">
</p>

<p align="center"><em>Figure 4. Overview of the workflow used for GPR acquisition, preprocessing, attribute extraction, and geotechnical validation.</em></p>


### 01_Data_Attribute_Extraction

This folder contains the consolidated GPR attribute databases used for the quantitative analysis of antenna-clearance effects. The datasets summarize the attributes extracted from the seven survey groups (G1–G7) at antenna clearances of **0, 10, and 40 cm** for the predefined analysis windows.

The folder contains three Excel databases:

- **`01_Master_height_comparison_database.xlsx`**  
  Master database containing the extracted GPR attributes and associated descriptive statistics for each survey group, antenna clearance, and analysis window. The database includes amplitude-, energy-, signal-quality-, frequency-, and spatial-coherence-based attributes, together with profile and acquisition metadata.

- **`02_Normalized_and_percentage_change_database.xlsx`**  
  Contains the selected GPR attributes normalized relative to the **0 cm antenna-clearance measurements**, together with the corresponding percentage changes. This database supports the direct comparison of attribute sensitivity to increasing antenna clearance across the seven survey groups.

- **`03_Mean_std_summary_database.xlsx`**  
  Summary database containing group-level descriptive statistics for each analysis window and antenna clearance. The reported statistics include the mean, standard deviation, median, minimum, and maximum values across the seven survey groups.

The databases include results for the shallow construction-transition window **W1 (8–18 ns)** and the deeper supporting-soil window **W3 (23–33 ns)** and provide the numerical data underlying the quantitative comparisons presented in the manuscript.



### 02_Key_Attributes

This folder contains the figures generated from the processed GPR data and extracted attributes and used in the manuscript for evaluating antenna-clearance effects and validating the GPR interpretation against independent geotechnical information.

> **Note:** PNG versions are used below for direct visualization in GitHub. The corresponding PDF files are retained in the folder as publication-quality versions.

#### Figure 5 — Representative GPR radargrams

<p align="center">
  <img src="02_Key_Attributes/Fig5a.png" width="32%" alt="Figure 5a - 0 cm antenna clearance">
  <img src="02_Key_Attributes/Fig5b.png" width="32%" alt="Figure 5b - 10 cm antenna clearance">
  <img src="02_Key_Attributes/Fig5c.png" width="32%" alt="Figure 5c - 40 cm antenna clearance">
</p>

<p align="center"><b>(a)</b> 0 cm &nbsp;&nbsp;&nbsp; <b>(b)</b> 10 cm &nbsp;&nbsp;&nbsp; <b>(c)</b> 40 cm</p>

Representative Group 1 radargrams acquired at antenna clearances of **0, 10, and 40 cm**, respectively. The predefined analysis windows **W1 (8–18 ns)** and **W3 (23–33 ns)** are highlighted to illustrate changes in the shallow and deeper GPR responses with increasing antenna clearance.

#### Figure 6 — GPR attributes within W1

<p align="center">
  <img src="02_Key_Attributes/Fig6.png" width="850" alt="Figure 6 - GPR attributes within W1">
</p>

Response of the four selected GPR attributes within the shallow **W1 (8–18 ns)** window as a function of antenna clearance for Groups G1–G7: (a) RMS amplitude, (b) signal energy, (c) signal-to-background ratio (SBR), and (d) adjacent-trace correlation.

#### Figure 7 — GPR attributes within W3

<p align="center">
  <img src="02_Key_Attributes/Fig7.png" width="850" alt="Figure 7 - GPR attributes within W3">
</p>

Response of the same four selected GPR attributes within the deeper **W3 (23–33 ns)** window for antenna clearances of 0, 10, and 40 cm.

#### Figure 8 — Statistical comparison within W1

<p align="center">
  <img src="02_Key_Attributes/Fig8_W1.png" width="850" alt="Figure 8 - Statistical comparison within W1">
</p>

Statistical comparison of RMS amplitude, signal energy, SBR, and adjacent-trace correlation within **W1** for the three antenna clearances.

#### Figure 9 — Statistical comparison within W3

<p align="center">
  <img src="02_Key_Attributes/Fig9_W3.png" width="850" alt="Figure 9 - Statistical comparison within W3">
</p>

Statistical comparison of the four selected GPR attributes within **W3** for the three antenna clearances.

#### Figure 10 — Borehole validation using HBR-01

<p align="center">
  <img src="02_Key_Attributes/Fig10a.png" width="48%" alt="Figure 10a - GPR radargram">
  <img src="02_Key_Attributes/Fig10b.png" width="48%" alt="Figure 10b - HBR-01 stratigraphy">
</p>

<p align="center"><b>(a)</b> GPR radargram &nbsp;&nbsp;&nbsp;&nbsp; <b>(b)</b> HBR-01 stratigraphy</p>

Primary borehole validation using **HBR-01**: (a) representative GPR radargram acquired at 10 cm antenna clearance with interpreted subsurface horizons, and (b) corresponding HBR-01 borehole stratigraphy.

#### Figure 11 — Laboratory and GPR comparison for HBR-01

<p align="center">
  <img src="02_Key_Attributes/Fig11.png" width="850" alt="Figure 11 - Laboratory and GPR comparison for HBR-01">
</p>

Laboratory and GPR comparison for **HBR-01**, including: (a) water content, (b) bulk density, (c) particle-size distribution, and (d) normalized GPR signal energy with depth.

#### Figure 12 — CPT–GPR comparison for Group G7

<table>
<tr>
<td align="center"><img src="02_Key_Attributes/Fig12a.png" width="400" alt="Figure 12a"><br><b>(a)</b> GPR — 10 cm</td>
<td align="center"><img src="02_Key_Attributes/Fig12b.png" width="400" alt="Figure 12b"><br><b>(b)</b> GPR — 40 cm</td>
</tr>
<tr>
<td align="center"><img src="02_Key_Attributes/Fig12c.png" width="400" alt="Figure 12c"><br><b>(c)</b> CPT-derived Vs</td>
<td align="center"><img src="02_Key_Attributes/Fig12d.png" width="400" alt="Figure 12d"><br><b>(d)</b> CPT parameters</td>
</tr>
</table>

CPT–GPR comparison for **Group G7**, including: (a) GPR radargram acquired at 10 cm antenna clearance, (b) GPR radargram acquired at 40 cm antenna clearance, (c) CPT-derived shear-wave velocity (Vs), and (d) cone resistance and sleeve-friction profiles. Five principal subsurface horizons are identified at approximately 0.25, 0.55, 1.00, 1.60, and 2.00 m depth.

#### Figure 13 — Supplementary borehole validation using HBR-03

<p align="center">
  <img src="02_Key_Attributes/Fig13a.png" width="48%" alt="Figure 13a - GPR radargram">
  <img src="02_Key_Attributes/Fig13b.png" width="48%" alt="Figure 13b - HBR-03 stratigraphy">
</p>

<p align="center"><b>(a)</b> GPR radargram &nbsp;&nbsp;&nbsp;&nbsp; <b>(b)</b> HBR-03 stratigraphy</p>

Supplementary borehole validation using **HBR-03**: (a) representative Group 4 GPR radargram acquired at 10 cm antenna clearance with interpreted horizons, and (b) corresponding HBR-03 borehole stratigraphy.

#### Figure 14 — Laboratory and GPR comparison for HBR-03

<p align="center">
  <img src="02_Key_Attributes/Fig14.png" width="850" alt="Figure 14 - Laboratory and GPR comparison for HBR-03">
</p>

Supplementary laboratory comparison for **HBR-03**, including water content, bulk density, particle-size distribution, and normalized GPR signal energy. This dataset is used as supplementary validation because fewer laboratory samples are available at HBR-03 than at HBR-01.

#### Figure 15 — Frequency-based GPR attributes

<table>
<tr>
<td align="center"><img src="02_Key_Attributes/Fig15a-df-w1.png" width="400" alt="Figure 15a"><br><b>(a)</b> Dominant frequency — W1</td>
<td align="center"><img src="02_Key_Attributes/Fig15b-spec-cet-w1.png" width="400" alt="Figure 15b"><br><b>(b)</b> Spectral centroid — W1</td>
</tr>
<tr>
<td align="center"><img src="02_Key_Attributes/Fig15c-df-w3.png" width="400" alt="Figure 15c"><br><b>(c)</b> Dominant frequency — W3</td>
<td align="center"><img src="02_Key_Attributes/Fig15d-spec-cet-w3.png" width="400" alt="Figure 15d"><br><b>(d)</b> Spectral centroid — W3</td>
</tr>
</table>

Frequency-based GPR attributes evaluated for W1 and W3. These attributes are provided as supplementary results because their response to antenna clearance is less consistent than that of the four attributes selected for the main analysis.

#### Figure 16 — Additional frequency-domain results

<p align="center">
  <img src="02_Key_Attributes/Fig16a-df-w3.png" width="48%" alt="Figure 16a">
  <img src="02_Key_Attributes/Fig16b-spec-cet-w3.png" width="48%" alt="Figure 16b">
</p>

Additional frequency-domain results retained as supplementary material.


### 03_Geotechnical_Validation

This folder contains the structured geotechnical datasets used for independent validation and interpretation of the GPR observations. The data include CPT measurements, CPT-derived shear-wave velocity profiles, and borehole/laboratory information from both recent and previous investigations.

The folder is organized into the following subfolders:

- **`CPT_Derived_Vs`**  
  Contains the processed CPT datasets and corresponding graphical profiles. The CSV files contain the CPT measurements used in the analysis, including cone resistance (`qc`), sleeve friction (`fs`), and friction ratio (`Rf`). Derived shear-wave velocity (`Vs`) profiles are also provided for comparison with the GPR-derived subsurface interfaces.

- **`Recent_BH`**  
  Contains the structured database compiled from the recent borehole and laboratory investigation conducted for the present project. The dataset includes borehole stratigraphy and available laboratory measurements, including water content, bulk density, and particle-size distribution, used for direct comparison with the GPR observations.

- **`Previous_BH`**  
  Contains the structured database compiled from historical borehole investigations available along the study section. These data provide additional information on subsurface stratigraphy and spatial variability and are used as supplementary geotechnical context for the GPR interpretation.

Together, these datasets provide independent geotechnical information for evaluating the correspondence between GPR reflections and changes in subsurface material properties and stratigraphy.
