
# ASU Thesis and Dissertation Template

## About this template

This template follows the guidelines set out by the [ASU Graduate College Format Manual](https://graduate.asu.edu/sites/default/files/2022-02/asu-graduate-college-format-manual.pdf). More information about [formatting your thesis](https://graduate.asu.edu/current-students/completing-your-degree/formatting-your-thesis-or-dissertation) can be found at the Graduate College website.

## Creating a New Thesis/Dissertation

To create a new article using this format:

```bash
quarto use template nicole-brewer/asu-thesis
```

This will create a new directory with an example document that uses this format.

## Using with an Existing Document

To add this format to an existing document:

```bash
quarto add nicole-brewer/asu-thesis
```

Then, add the format to your document options:

```yaml
format:
  asu-thesis-pdf: default
```    

## Options

*TODO*: If your format has options that can be set via document metadata, describe them.

## Example

Here is the source code for a minimal sample document: [template.qmd](template.qmd).

