# osa-streamlit

---

[![OSA-improved](https://img.shields.io/badge/improved%20by-OSA-yellow)](https://github.com/aimclub/OSA)

---

## Overview

osa-streamlit simplifies repository documentation by automatically generating README files. It empowers users to create high-quality documentation quickly, supports various language models, and offers configuration options for workflows and licensing – even for private repositories.

---

## Table of Contents

- [Core features](#core-features)
- [Installation](#installation)
- [Contributing](#contributing)
- [Citation](#citation)

---
## Core features

1. **README Generation**: Automates the creation of README files for repositories using an LLM, potentially improving documentation quality and reducing manual effort.
2. **LLM Provider Integration**: Supports multiple Large Language Model (LLM) providers (currently ITMO with wq_gemma3_27b_8q), allowing users to choose the best model for their needs.
3. **Configuration Options**: Provides a sidebar in the Streamlit app with configurable options such as repository URL, LLM provider selection, translation of directories, workflow generation and license enforcement.
4. **Console Output Display**: Displays real-time console output from the underlying 'osa-tool' process within the Streamlit application, providing feedback on progress and potential errors.

---

## Installation

Install osa-streamlit using one of the following methods:

**Build from source:**

1. Clone the osa-streamlit repository:
```sh
git clone https://github.com/DRMPN/osa-streamlit
```

2. Navigate to the project directory:
```sh
cd osa-streamlit
```

3. Install the project dependencies:

```sh
pip install -r requirements.txt
```

---

## Contributing

- **[Report Issues](https://github.com/DRMPN/osa-streamlit/issues)**: Submit bugs found or log feature requests for the project.

---

## Citation

If you use this software, please cite it as below.

### APA format:

    DRMPN (2025). osa-streamlit repository [Computer software]. https://github.com/DRMPN/osa-streamlit

### BibTeX format:

    @misc{osa-streamlit,

        author = {DRMPN},

        title = {osa-streamlit repository},

        year = {2025},

        publisher = {github.com},

        journal = {github.com repository},

        howpublished = {\url{https://github.com/DRMPN/osa-streamlit.git}},

        url = {https://github.com/DRMPN/osa-streamlit.git}

    }

---
