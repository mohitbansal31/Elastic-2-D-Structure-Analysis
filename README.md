# Structural Analysis using Direct Stiffness Method

This repository contains the report detailing the implementation and findings derived from the Python code developed to execute the Direct Stiffness Method (DSM) for structural analysis. The report highlights the comparison of results obtained from the developed code with those from STAAD Pro.

## Table of Contents

- [Introduction](#introduction)
- [Report Overview](#report-overview)
- [Key Findings](#key-findings)
- [File Description](#file-description)
- [Conclusion](#conclusion)
- [Contributions](#contributions)
- [License](#license)

## Introduction

The Direct Stiffness Method (DSM) is a fundamental approach in structural analysis used to analyze the behavior of structures under various loading conditions. This report presents the results of implementing DSM in Python, focusing on its application in structural analysis and comparison with commercial software, STAAD Pro.

## Report Overview

The key sections of the report include:

- **Moments**: This section discusses the sample input files for member data used in the analysis.
- **Reactions**: An overview of the reaction forces computed in the analysis.
- **Structure Analysis**: Detailed descriptions of the two structures analyzed, including their resultant displacements and a comparative analysis with STAAD Pro.

### File Description

- **website-1733057804095-Report.pdf**: This document includes:
  - **Moments**: Sample input files for member actions and loading.
  - **Reactions**: Tabulated results showing the reactions at supports.
  - **Structures Analysis**:
    - **Structure 1**: Resultant displacements from the analysis and comparisons with STAAD Pro outputs.
    - **Structure 2**: Further analyses highlighted with graphical presentations and numerical comparisons.

## Key Findings

In summary, the Python code developed for implementing the Direct Stiffness Method showed promising results. The findings include:

- A comparison with STAAD Pro yielded a marginal difference of approximately 2%, indicating the code's effectiveness.
- The differences between the two methods can be attributed to factors such as numerical approximation, element discretization, and computational precision.
- The code's capabilities were enhanced by incorporating considerations for support settlement in a portal frame, contributing to a more comprehensive analysis of real-world structural behavior.

## Conclusion

The report demonstrates the viability of using the Direct Stiffness Method in Python for structural analysis. The results obtained show a close alignment with established software, validating the approach and its potential application in engineering practices.

## Contributions

Contributions to this project are welcome! Please see [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines on how to contribute.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- A special thanks to the contributors of the DSM methodology and techniques. 
- Acknowledgment of tools and libraries used in the implementation of the project.

For any further questions or inquiries, please feel free to reach out via GitHub issues or directly through the contact information provided in the report.