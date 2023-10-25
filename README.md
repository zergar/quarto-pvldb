# Association of Computing Machinery (ACM)

This Quarto format will help you create documents for the Proceedings of the International Conference on Very Large Data Bases (PVLDB). The [template](https://github.com/cwida/pvldbstyle/archive/master.zip) is based on the Article Template of the Association for Computing Machinery. To learn more about ACM publications, see [ACM's Information for Authors page](https://www.acm.org/publications/authors/information-for-authors). For more about Quarto and how to use format extensions, see <https://quarto.org/docs/journals/>.

## Creating a New Article

You can use this as a template to create an article for the Association of Computing Machinery. To do this, use the following command:

```quarto use template quarto-journals/acm```

This will install the extension and create an example qmd file and bibiography that you can use as a starting place for your article.


## Installation For Existing Document

You may also use this format with an existing Quarto project or document. From the quarto project or document directory, run the following command to install this format:

```quarto add quarto-journals/acm```

## Usage 

To use the format, you can use the format names `acm-pdf` and `acm-html`. For example:

```quarto render article.qmd --to acm-pdf```

or in your document yaml

```yaml
format:
  pdf: default
  acm-pdf:
    keep-tex: true    
```

You can view a preview of the rendered template at <https://quarto-journals.github.io/acm/>. 

