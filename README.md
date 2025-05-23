# ESA-PhiLab GitHub Repository Template

Welcome to the official ESA-PhiLab repository. This template ensures that all projects conform to ESA-PhiLab's guidelines for reproducibility, licensing, and collaboration.

## 📌 Project Title
> Replace this with your project name.

## 👥 Authors
List all project contributors. Preferably include links to their professional profiles.

- Name One ([profile](https://example.com))  
- Name Two ([profile](https://example.com))

## 📖 Project Reference
Specify the type and context of the project.

- Example: ESA Φ-lab Research Fellowship — [Link to ESA page](https://philab.esa.int)

## 📝 Abstract
Provide a concise summary of the project goals, methodology, and outcomes.

## 🛠️ How to Use
Detailed instructions to set up and run the project.

### Requirements
This repository uses a modern Python environment standard:
- Python ≥ 3.9
- Dependencies are specified in the `pyproject.toml` file.

To install:
```bash
pip install .
```
Or using PDM:
```bash
pdm install
```

## 📚 Citations
Please cite the following works if you use this code:
- [Reference Paper 1]
- [Reference Paper 2]

## 📂 Repository Structure
```
├── LICENSE
├── README.md
├── pyproject.toml      # project metadata & dependencies
├── setup.cfg           # optional packaging config
├── environment.yml     # optional environment specification
├── src/                # source code & Python package
│   └── your_package/   # replace with your package name
├── notebooks/          # Jupyter notebooks for experiments or analysis
├── papers/             # manuscript sources (LaTeX, figures, assets)
├── data/               # raw/processed datasets or external links
├── scripts/            # utility scripts and entry points
├── tests/              # unit and integration tests
├── docs/               # documentation (Sphinx, MkDocs, GitHub Pages)
└── examples/           # usage examples and demos
```

## 📄 License
This project is licensed under the **CC BY-NC-ND 4.0** license. See the [LICENSE](./LICENSE) file or read more at [creativecommons.org](https://creativecommons.org/licenses/by-nc-nd/4.0/).

## 📊 Dataset Hosting
Datasets are either included in `data/` or hosted externally:
- [Zenodo](https://zenodo.org)
- [Hugging Face Datasets](https://huggingface.co/datasets)

Ensure external links are functional and persistent.

## 🌐 GitHub Pages
This repository supports GitHub Pages. Request support to enable and configure the page if needed.

---

*For internal use only: This repository conforms to the ESA-PhiLab development and archiving standards.*
