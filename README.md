# Quarto Template - American Chemical Society

## Using the Template

You can use this as a template to create an article for an ACS journal. To do this, use the following command:

```quarto use template quarto-journals/acs```

This will install the extension and create an example qmd file and bibiography that you can use as a starting place for your article.


## Installation For Existing Document

You may also use this format with an existing Quarto project or document. From the quarto project or document directory, run the following command to install this format:

```quarto install extension quarto-journals/acs```

This will install the ACS extension. To use the extension, you can use the format names `acs-pdf` and `acs-html`. For example:

```quarto render article.qmd --to acs-pdf```

or in your document yaml

```yaml
format:
  pdf: default
  acs-pdf:
    keep-tex: true    
```

## Notes

The American Chemical Society recommends that you use the `achemso` package for LaTeX when preparing a manuscript for one of their journals. Learn more about `achemso` [here](https://www.ctan.org/tex-archive/macros/latex/contrib/achemso).
