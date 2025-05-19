# Project Elara Technical Overview

This repository houses Project Elara's technical overview. [See it live online](https://elaraproject.github.io/elara-technical-overview/).

> Everything in this report is released to the **public domain** like the rest of [Project Elara](https://github.com/elaraproject/), meaning it is essentially **unlicensed research**, so you can use it for basically any project you want, _however_ you want, with or without attribution.

## Development

This is a [MyST](https://mystmd.org/) site. To get started, first clone the repository:

```sh
git clone https://github.com/elaraproject/2024-research-report
```

Ensure you have [Python](https://www.python.org/) and [pip](https://pypi.org/project/pip/) installed. Then install MyST with:

```sh
pip install mystmd
```

To start a live development server, run:

```
myst start
```

To build the PDF, you must have [LaTeX installed](https://www.latex-project.org/get/). With a working LaTeX installation, the PDF can then be built with:

```
myst build --pdf
```
