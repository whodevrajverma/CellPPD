# CellPPD: In Silico Tool for Designing and Predicting Highly Potent Cell-Penetrating Peptides

**CellPPD** is a specialized computational resource developed to identify, design, and scan for **Cell-Penetrating Peptides (CPPs)**. These short peptides (typically under 30 amino acids)
serve as versatile transport vehicles for delivering molecular cargoes—such as oligonucleotides, small molecules, and proteins—into the interior of cells, overcoming the challenge of low bioavailability.

**Web Server:** https://webs.iiitd.edu.in/raghava/cellppd/


## Citation

Gautam, A., Chaudhary, K., Kumar, R., Sharma, A., Kapoor, P., Tyagi, A., & Raghava, G. P. S. (2013).
**In silico approaches for designing and predicting highly effective cell penetrating peptides.** *Journal of Translational Medicine*, 11, 74.
https://doi.org/10.1186/1479-5876-11-74


## About the Research

The therapeutic potential of CPPs is vast, but experimental identification is time-consuming. CellPPD was developed to allow for the rapid screening and discovery of these peptides using machine learning models
trained on experimentally validated data.

* **Dataset:** The models were developed using a main dataset of **708 experimentally validated CPPs** and an equal number of non-CPPs.
* **Methodology:** The platform utilizes **Support Vector Machine (SVM)** models alongside motif-based searches to provide high-precision predictions.


## Key Features

### 1. Robust Predictive Models

* **Multiple Input Features:** Predictions are based on amino acid composition, dipeptide composition, binary profiles, and physicochemical properties.
* **Hybrid Approach:** Combines SVM-based machine learning with a **motif-based search** (using 58 identified CPP-specific motifs) to enhance accuracy.
* **Performance:** The hybrid model achieved a maximum accuracy of **81.31%** and a Matthews Correlation Coefficient (MCC) of 0.63.

### 2. Peptide Design and Scanning

* **In Silico Design:** This module allows users to generate all possible single-point mutations of a peptide and predict how each change affects its cell-penetrating potential.
* **Protein Scanning:** Users can scan a whole protein sequence to identify specific regions that could act as effective CPPs.

### 3. Integrated Web-Bench

* **Sequence Analysis:** Provides a detailed analysis of physicochemical properties (e.g., hydrophobicity, charge, molecular weight) for submitted sequences.
* **Similarity Search:** Integrated **BLAST** search to compare query sequences against a curated database of known CPPs.
* **User-Friendly Interface:** Supports single sequence submission, batch processing, and structure-based property analysis.


## Applications

* **Drug Delivery:** Identifying and optimizing peptide carriers to improve the intracellular delivery of poorly permeable drugs.
* **Gene Therapy:** Designing carriers for the effective transport of antisense oligonucleotides or siRNA into target cells.
* **Biomolecular Research:** Using CPPs as tools to deliver molecular probes or proteins to study intracellular processes in real-time.


## Contact & Authors

**Prof. Gajendra P. S. Raghava** (Corresponding Author)

raghava@iiitd.ac.in

Department of Computational Biology, Indraprastha Institute of Information Technology (IIIT Delhi), New Delhi, India.


## Support

The development of CellPPD was supported by the **Department of Biotechnology (DBT)** and the **Council of Scientific and Industrial Research (CSIR)**, Government of India.
