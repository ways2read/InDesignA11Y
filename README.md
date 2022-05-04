# InDesignA11Y

The goal of this repository is to present code examples to help InDesign developers improve the accessibility of exporting to reflowable EPUB 3.

## Structure
For each requirement reported in the [InDesign - requirements grid](https://docs.google.com/spreadsheets/d/1QlnR6X7DwoSye_69CsbjJmTv3NAr3cvxWTwTTyN1jBI/edit#gid=662527895) that we propose to work on, we are creating a folder in the repository and an [issue](https://github.com/ways2read/InDesignA11Y/issues) with the explanation.

In each folder you can find:

- the source InDesign file (named `0-...`)
- the EPUB 3 file exported by InDesign, without any modification (named `1-...`)
- the EPUB 3 file fixed by hand, as we would like InDesign to export the content (named `2-...`)

## References

- [InDesign - requirements grid](https://docs.google.com/spreadsheets/d/1QlnR6X7DwoSye_69CsbjJmTv3NAr3cvxWTwTTyN1jBI/edit#gid=662527895)
- [DAISY Knowledge Base](http://kb.daisy.org/publishing/docs/)

## Validation

Two essential tools for checking EPUB 3 from InDesign are the validators that are used by the publishing industry:

- [EPUBCheck](https://github.com/w3c/epubcheck) is a tool to validate the conformance of EPUB publications against the EPUB specifications
- [Ace](https://daisy.github.io/ace/), the Accessibility Checker for EPUB, is a tool developed by the DAISY Consortium to assist with the evaluation of accessibility features of EPUB publications
