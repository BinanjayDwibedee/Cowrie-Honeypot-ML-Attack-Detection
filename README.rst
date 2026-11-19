# Cowrie Honeypot – Machine Learning Based Attack Detection

**Developed and Customized by: Binanjay Dwibedee**

**GitHub:** https://github.com/BinanjayDwibedee/Cowrie-Honeypot-ML-Attack-Detection

**Project:** Machine Learning-Based SSH Honeypot Attack Detection and Analysis

---

## Copyright and Attribution

SPDX-FileCopyrightText: 2014 Upi Tamminen <desaster@gmail.com>  
SPDX-FileCopyrightText: 2014-2025 Michel Oosterhof <michel@oosterhof.net>  
SPDX-FileCopyrightText: 2026 Binanjay Dwibedee (original ML-based modifications and contributions)

SPDX-License-Identifier: BSD-3-Clause

This project is based on the original open-source Cowrie SSH and Telnet Honeypot. Original Cowrie copyrights, licenses, and contributor acknowledgments are retained.

## About This Project

This repository contains the Cowrie SSH and Telnet Honeypot, extended with a Machine Learning-based attack detection and analysis workflow.

The project aims to capture attacker activities, analyze honeypot logs, identify suspicious command patterns, and classify potential cyberattacks using machine learning techniques.

### Main Objectives

- Deploy an SSH/Telnet honeypot to capture real-world attack attempts.
- Collect and analyze attacker interaction logs.
- Extract useful features from Cowrie JSON log files.
- Detect suspicious commands and malicious activities.
- Apply machine learning techniques for attack pattern detection.
- Generate graphical analysis and attack statistics.
- Automatically generate HTML and CSV detection reports.

### Project Developer

**Binanjay Dwibedee**

GitHub: https://github.com/BinanjayDwibedee

### Original Cowrie Project

https://github.com/cowrie/cowrie

Original documentation: https://docs.cowrie.org/

Original maintainers and contributors are acknowledged in the original Cowrie project.

---

## Machine Learning Attack Detection

The additional ML component analyzes Cowrie JSON logs to identify suspicious attacker behavior.

Key components include:

- JSON log processing
- Data preprocessing
- Feature extraction
- Suspicious command analysis
- Attack pattern identification
- Machine learning-based detection
- Visualization and reporting

### Generated Outputs

- Attack detection results in CSV format
- Automated HTML analysis report
- Graphs and attack statistics
- Session and command analysis

---

## Original Cowrie Documentation

For installation, configuration, and usage of the original Cowrie honeypot, refer to:

https://docs.cowrie.org/en/latest/index.html

## License

This project retains the original Cowrie BSD-3-Clause license. See the repository's LICENSE file for complete licensing terms.

Original Cowrie developers and contributors retain their respective copyrights. Copyright attribution for additional modifications applies only to work contributed by the respective author.
