# OpenAI Research

![A hero image of data scientists working collaboratively](https://raw.githubusercontent.com/alan-turing-institute/turing-commons/main/docs/assets/images/illustrations/data-science.png)

## About this Repository

This repository contains documentation and notes related to exploratory research on OpenAI's Playground (i.e. their API for interacting with their currently public models + ChatGPT).

This repository is based on this [reproducible project template](https://github.com/alan-turing-institute/reproducible-project-template), which follows the recommendations and guidance provided in *[The Turing Way](https://the-turing-way.netlify.app/welcome)* handbook to data science.
When reusing this repository, please update information on your README page with information about your project.

### Repo Structure

The structure of this repostiory follows the above template, and is inspired by [Cookie Cutter Data Science](https://github.com/drivendata/cookiecutter-data-science):

```
├── LICENSE
├── README.md          <- The top-level README for users of this project.
├── CODE_OF_CONDUCT.md <- Guidelines for users and contributors of the project.
├── CONTRIBUTING.md    <- Information on how to contribute to the project.
├── data
│   ├── processed      <- The final, canonical data sets for modeling.
│   └── raw            <- The original, immutable data dump.
│
├── docs               <- A default Sphinx project; see sphinx-doc.org for details
│
├── models             <- Trained and serialized models, model predictions, or model summaries
│
├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
│                         the creator's initials, and a short `-` delimited description, e.g.
│                         `1.0-jqp-initial-data-exploration`.
│
├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
│   └── figures        <- Generated graphics and figures to be used in reporting
│
├── project_management <- Meeting notes and other project planning resources
│
├── src                <- Source code for use in this project.
│   │
│   ├── data           <- Scripts to download or generate data
│   │   └── make_dataset.py
│   │
│   ├── models         <- Scripts to train models and then use trained models to make
│   │   │                 predictions
│   │   ├── predict_model.py
│   │   └── train_model.py
│   │
│   └── visualisation  <- Scripts to create exploratory and results oriented visualisations
│       └── visualise.py
└──
```

❗️Disclaimer
---

The content of this repository does not constitute a professional audit of OpenAI's models or APIs, nor does it aspire to do so. Rather, it is intended to provide a well-documented and open space for researchers interested in exploring the benefits and risks of LLMs in a semi-structured but exploratory manner.

📫 Contact
---

For any queries, you can either a) raise an issue or b) email [cburr@turing.ac.uk](mailto:cburr@turing.ac.uk) directly.

♻️ License
---

This work is licensed under the MIT license (code) and Creative Commons Attribution 4.0 International license (for documentation).
You are free to share and adapt the material for any purpose, even commercially,
as long as you provide attribution (give appropriate credit, provide a link to the license,
and indicate if changes were made) in any reasonable manner, but not in any way that suggests the
licensor endorses you or your use, and with no additional restrictions.
