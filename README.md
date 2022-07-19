# InDesignA11Y

The goal of this repository is to list all the requirements for creating born accessible EPUB 3 that are not currently available in InDesign or that can be improved. We present detailed issues and code examples to help InDesign developers improve the accessibility of exporting to reflowable EPUB 3.

## Structure
For each article reported in the [DAISY Knowledge Base](http://kb.daisy.org/publishing/docs/) whose functionality is not available in InDesign ore that can be improved, we created an [issue](https://github.com/ways2read/InDesignA11Y/issues) with the link to the Knowledge Base article and we are adding a detailed explanation, while creating a folder in the repository for the code examples.

In each folder you can find:

- the source InDesign file (named `0-...`)
- the EPUB 3 file exported by InDesign, without any modification (named `1-...`)
- the EPUB 3 file fixed by hand, as we would like InDesign to export the content (named `2-...`)

## Validation

Two essential tools for checking EPUB 3 from InDesign are the validators that are used by the publishing industry:

- [EPUBCheck](https://github.com/w3c/epubcheck) is a tool to validate the conformance of EPUB publications against the EPUB specifications
- [Ace](https://daisy.github.io/ace/), the Accessibility Checker for EPUB, is a tool developed by the DAISY Consortium to assist with the evaluation of accessibility features of EPUB publications
