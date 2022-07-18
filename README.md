# acs

This is a Quarto template that assists you in creating a manuscript for American Chemical Society journals (based upon the `achemso` LaTeX package). You can learn more about the `achemso` package [on CTAN](https://www.ctan.org/tex-archive/macros/latex/contrib/achemso).

## Creating a New Article

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

### Template Preview

You can view a preview of the rendered template at <https://quarto-journals.github.io/acs/>. 




