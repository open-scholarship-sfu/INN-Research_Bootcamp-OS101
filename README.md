# Open Scholarship 101 Workshop Slides

This repository contains the source files for the **Open Scholarship 101** workshop slides, created using **Quarto**. The repository is used for version control, collaborative development, and long-term maintenance of workshop materials.

The workshop is part of the **Summer Research Bootcamp** hosted by Simon Fraser University's Institute for Neuroscience and Neurotechnology (INN), which provides undergraduate and graduate students with practical research skills and professional development opportunities. The session introduces the principles and practices of open scholarship and how they can be integrated into everyday research workflows.

## Repository Structure

```text
.
├── inn_rb-os101_slides.qmd              # Main slide deck
├── _quarto.yml                          # Quarto project configuration
├── assets/                              # Figures, logos, and graphics
├── resources/                           # Supporting materials
├── references.bib                       # Bibliography (if applicable)
└── README.md
```

## Requirements

To build the slides locally, install:

* Quarto
* A code editor interface such as Positron, RStudio or VS Code (recommended)

Verify your installation:

```bash
quarto check
```

## Rendering the Slides

Render the presentation with:

```bash
quarto render
```

Or preview while editing:

```bash
quarto preview
```

## Editing Guidelines

* Make changes through feature branches when possible.
* Write clear, descriptive commit messages.
* Keep slide content concise and accessible.
* Store images and other media in the `assets/` directory.
* Use relative file paths throughout the project.

## Topics Covered

The workshop provides an introduction to open scholarship, including topics such as:

* The why and what of open scholarship
* Benefits and challenges of open and reproducible research
* Practical tools and resources for adopting open research practices

## Contributing

Contributions, suggestions, and corrections are welcome. Please:

1. Fork the repository.
2. Create a feature branch.
3. Commit your changes.
4. Open a pull request with a brief description of the proposed updates.

## License

Unless otherwise specified, the workshop materials are licensed under the **Creative Commons Attribution-ShareAlike 4.0 International (CC BY SA 4.0)** license.

## Acknowledgements

These materials were developed for the **Open Scholarship 101** workshop delivered as part of the **Simon Fraser University Summer Research Bootcamp**. They draw on resources from the SFU Open Scholarship initiative and the broader open science community.

---

*This repository is intended to support the development, maintenance, and reuse of workshop materials while promoting transparent, reproducible, and collaborative educational practices.*
