# USFCA Thesis Template
This is unofficial template, use at your own discretion.

Quarto extension for a USFCA Economics Master's thesis. If this is useful for you give my repo a ★.

This template is based on the Latex Template I made in overleaf (Mar 9 2023).

Everything you need to know to get started you can find in [this official guide](https://quarto.org/docs/guide/).

## Where to Use

If this your first time using quarto, you first need to install it into your editor and install tinyTeX to render LaTeX PDFs.

### RStudio
Install quarto and tinyTeX.
```{r, eval = F}
install.packages(quarto, tinytex)
```

### Visual Studio Code
Go to Extensions -> look up "Quarto" -> install
Then run the following command in the terminal if you don't have tinyTeX installed.
```
quarto install tinytex

```

## Add Quarto Template

Installing the extension You will need to do this to get all the folders
with tex files.

Run the following command in your terminal.

    quarto add template nikitoshina/USFCA-Thesis-Template

Once you do that you can render from within the folder.

    cd your_folder

You can render your project from within your folder by running following command in terminal.

    quarto render

Installation or updating for an existing document. You may also use this
format with an existing Quarto project or document. But you will need to
have all the tex folders already (see above).

    quarto install extension nikitoshina/USFCA-Thesis-Template

## Usage 

Your first chapter will go into `index.qmd` and add your other chapters into `/Chapters` folder. Look at the file `_quarto.yml`. For citations use Zotero.

