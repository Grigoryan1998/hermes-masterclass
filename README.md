# HERMES Masterclasses

An educational website for the **HERMES Masterclasses**, built with [Quarto](https://quarto.org/) and published with GitHub Pages.

## 🌐 View the website

**[Open the HERMES Masterclasses website](https://grigoryan1998.github.io/hermes-masterclass/)**

You do not need to install anything to view the website — just open the link above in a web browser.

## About the project

The site provides introductory material and learning activities related to the HERMES experiment, including:

- an introduction to HERMES;
- basic particle-physics material;
- interactive masterclass missions;
- an analysis lab;
- results and supporting material;
- resources for teachers and tutors.

## Local preview

To run the website locally, first install [Quarto](https://quarto.org/docs/get-started/), then clone the repository:

```bash
git clone https://github.com/Grigoryan1998/hermes-masterclass.git
cd hermes-masterclass
```

Start a local preview with:

```bash
quarto preview
```

Quarto will print a local address that you can open in your browser.

## Publishing

Publishing is automated with GitHub Actions. Any push to the `main` branch triggers the Quarto publishing workflow, which builds the site and deploys it to the `gh-pages` branch.

## Project structure

- `_quarto.yml` — website configuration
- `index.qmd` — homepage
- `about-hermes.qmd` — HERMES experiment overview
- `physics-basics.qmd` — introductory physics material
- `mission-*.qmd` — masterclass mission pages
- `analysis-lab.qmd` — analysis activities
- `results.qmd` — results page
- `teachers.qmd` — teacher and tutor resources
- `assets/` — images and other website assets
- `styles.css` — custom website styling

## Repository

Source code and website content are maintained at:

https://github.com/Grigoryan1998/hermes-masterclass
