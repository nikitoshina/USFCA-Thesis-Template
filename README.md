# USFCA Thesis Template

This is an unofficial template for USFCA Economics Master's theses, created using the Quarto extension. Please use at your own discretion. If you find it helpful, give this repo a star ★.

## Getting Started

To use this template, you will need to install Quarto and TinyTeX.

### RStudio

Install Quarto and TinyTeX by running the following command in R:

```
install.packages(c("quarto", "tinytex"))
```

### Visual Studio Code

Install the Quarto extension by going to Extensions -> search for "Quarto" -> install. Then run the following command in the terminal if you don't have TinyTeX installed:

```
quarto install tinytex
```

## Adding the Quarto Template

To add the template to your project, run the following command in your terminal:

```
quarto use template nikitoshina/USFCA-Thesis-Template
```

This will download all the necessary folders with the LaTeX files for your thesis. You can render your project from within your folder by running the following command in terminal:

```
quarto render
```

## Usage

Your first chapter should be written in index.qmd, and you can add additional chapters to the /Chapters folder. For citations, we recommend using Zotero. Please see the `_quarto.yml` file for additional configuration options.

For more information on getting started with Quarto, please see the [official guide](https://github.com/nikitoshina/USFCA-Thesis-Template).

