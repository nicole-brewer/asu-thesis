# asu-quarto-thesis Format

| :warning: WARNING          |
|:---------------------------|
| This repo is under active development and construction.  |

This repo contains a custom Quarto extension for the ASU Thesis/Dissertation. When completed, you will be able to use this extension to write your thesis entirely in a collection markdown files, without having to mess with any LaTeX. This is made possible by some metadata you can set in `template.qmd`. 

As I'm interested in others using this template, I've decided to base my template off of [shumway's](https://github.com/shumway) [asudis](https://github.com/shumway/asudis/) instead of [Robert Cutter's](GarenSidonius) [ASU-Dissertation-Template](https://github.com/GarenSidonius/ASU-Dissertation-Template)
https://github.com/nicole-brewer/asudis/tree/master because I don't expect everyone to be able to use Docker, even though it affords cleaner code and more modern LaTeX conveniences. I haven't many changes other than rearranging the code so that it is more easy to template. There are also some changes that were made to accommodate some [code injected by Pandoc on render](https://github.com/quarto-dev/quarto-cli/discussions/6513?notification_referrer_id=NT_kwDOATuoV7M3MzczNzU2MjI0OjIwNjg2OTM1#discussioncomment-6764841). 

## Goals

- [x] Quarto metadata for easily changing text in front and back matter
- [ ] Support for `.qmd` files as chapters or sub-chapters
- [ ] Support chapter content rearrangement with Scrivener using [ScrivQ](https://github.com/bcdavasconcelos/ScrivQ) or [scrivomatic](https://github.com/iandol/scrivomatic) 


## Installing

```bash
quarto use template nicole-brewer/asu-thesis
```

This will install the extension and create an example qmd file that you can use as a starting place for your article.

## Using

*TODO*: Describe how to use your format.

## Format Options

*TODO*: If your format has options that can be set via document metadata, describe them.

## Example

Here is the source code for a minimal sample document: [template.qmd](template.qmd).

