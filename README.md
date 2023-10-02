# SpectreMeltdownTracker
[![Build Status](https://travis-ci.org/your-username/vulnerability-tracker.svg?branch=master)](https://travis-ci.org/your-username/vulnerability-tracker)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE.md)

Centralized database monitoring system vulnerabilities to Spectre and Meltdown attacks. Contribute to enhance security awareness. 🛡️

## Vulnerability Tracker

Welcome to the Spectre/Meltdown Vulnerability Tracker repository! This project aims to create a central database to track the vulnerability status of systems regarding Spectre and Meltdown attacks. By collecting information on which systems are still vulnerable, we can raise awareness and facilitate the implementation of necessary security measures.

## Table of Contents
- [How it Works](#how-it-works)
- [Getting Started](#getting-started)
- [Contributions](#contributions)
- [Contribution Guidelines](#contribution-guidelines)
- [Dependencies](#dependencies) 
- [Installation](#installation)
- [Disclaimer](#disclaimer)
- [Credits](#credits)
- [License](#license)

## How it Works

We provide a script (`vuln_tracker.py`) that gathers information about the vulnerability status of your system. This includes details about installed security patches, processor information, and any other relevant data. The collected information is then contributed to this central repository to create a comprehensive overview.

## Getting Started

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/arnavgupta2003/SpectreMeltdownTracker.git
   cd SpectreMeltdownTracker
   ```

2. **Run the Script:**
   Execute the script to gather information about your system. (Just need to run Make)
   ```bash
   make
   ```

4. **Contribute:**
   After running the script, follow the instructions to contribute the collected data to this repository. Create a pull request with the generated report.

## Contributions

We welcome contributions from the community to improve the accuracy and coverage of our vulnerability database. To contribute:

1. Fork the repository.
2. Clone your forked repository.
3. Run the script on your system and follow the instructions to generate a report.
4. Commit the generated report to your forked repository.
5. Create a pull request with a descriptive title and details about the changes.

Also consult [CONTRIBUTING.md](https://github.com/arnavgupta2003/SpectreMeltdownTracker/blob/main/CONTRIBUTING.md)

## Contribution Guidelines

- Include information about how to run tests and check code coverage.
- Specify any coding standards or conventions contributors should follow.


1. **Fork the Repository:**
   Fork the repository to your GitHub account before making any changes.
   
2. **Code Standards:**
   Follow the established coding standards and conventions in the project. Maintain a clean and readable codebase.

3. **Documentation:**
   Update documentation to reflect your changes. This includes the `README.md` file and any relevant inline documentation.

4. **Commit Messages:**
   Write clear and concise commit messages that describe the purpose of each commit.

5. **Pull Request:**
   Create a pull request to propose your changes. Provide a detailed description of your changes, including any necessary context or background information.

6. **Code Review:**
   Expect and participate in code reviews. Address feedback and make necessary adjustments to your code.

7. **Merging:**
    Once your changes have been approved, they will be merged into the main repository.

Thank you for contributing to the security awareness and improvement of our vulnerability tracker!



## Dependencies

This package is designed to run on Linux and requires the following dependencies:

- `gcc`: GNU Compiler Collection
- `ld`: The GNU linker
- `binutils`: A collection of binary tools
- `sh`: The Bourne Shell (used for running scripts in the terminal)
- `make`: Make is a build automation tool that streamlines software project compilation using a Makefile to define and execute tasks.


## Installation

There are no additional dependencies beyond Python's standard library. Except for:
- Linux System
- GCC
- LD
- Make

## Installation (Advanced)
For users with custom Linux environments, you may need to manually install additional dependencies. Make sure you have gcc, ld, binutils, and sh available in your system.

## Disclaimer

This project is for informational purposes only and should not be considered a comprehensive solution for assessing system security. While the provided script (`vuln_tracker.py`) aims to collect relevant data about system vulnerabilities, it does not guarantee absolute accuracy. The information gathered is based on the system's current configuration and may not cover all potential security aspects.

**Use at Your Own Risk:**
The data generated by this script should be interpreted with caution, and users are strongly advised to perform additional security assessments by consulting with cybersecurity professionals or using specialized security tools. The project contributors and maintainers disclaim any liability for damages or issues arising from the use of this information.

**Professional Security Assessments:**
For critical systems or applications, it is recommended to conduct thorough, professional security assessments to identify and address vulnerabilities. This script serves as a supplementary tool for awareness but should not replace comprehensive security evaluations.



## Credits

This project includes the use of the Intel manufacture checker script. We want to express our gratitude to the authors and contributors of the Intel manufacture checker script for their valuable work in enhancing system security.
[Link](https://www.intel.com/content/www/us/en/developer/articles/technical/software-security-guidance/secure-coding/spectre-and-meltdown-checker-script.html#:~:text=The%20Spectre%20and%20Meltdown%20Checker,and%20rogue%20system%20register%20read)


## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
