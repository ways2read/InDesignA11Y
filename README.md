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

## Adobe Severity Levels

### Severity 1: 
- Does not conform with WCAG 2.1 Level AA criteria and blocks core user tasks (no known workaround). 
- The end user is not able to access the product/content or complete core user tasks or activities. 
### Severity 2: 
- Does not conform with WCAG 2.1 Level AA criteria and is either non-blocking for core user tasks or blocking for non-core user tasks.
- Workarounds are available and discoverable for the end user to complete core user tasks or the end user is not able to complete non-core user tasks. 
### Severity 3: 
- Does not conform with WCAG 2.1 Level AA criteria but has lower user impact. 
- The WCAG violation is present in areas not frequently visited by end users or has a lower impact on overall accessibility and usability. Issues with negligible user impact may be given an exception by the Adobe corporate accessibility team. 
### Severity 4: 
- A potential usability issue but not a WCAG 2.1 Level AA conformance issue. 
- The end user experience is not optimized. Although conforming, the end user experience could be significantly improved through research, usability studies, or implementation of best practices”
