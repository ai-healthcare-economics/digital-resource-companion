# LaTeX Resources

The repository includes one worked-example file, one supplemental-resource file, and one reference-resource file for each chapter. The chapter wrapper files are assembled by `latex/main.tex`.

## Compile

From the `latex` directory run:

```text
xelatex main.tex
biber main
xelatex main.tex
xelatex main.tex
```

The LaTeX source uses `book`, `fontspec`, `microtype`, `amsmath`, `booktabs`, `longtable`, `tabularx`, `ragged2e`, `enumitem`, `hyperref`, and `biblatex`.

## Adaptation

The worked examples use synthetic inputs unless a source is stated. Preserve the original file, create a local version, record every changed assumption, and keep the evidence cut-off, resource version, accountable owner, review date, and decision conditions visible.
