<h1 align="center">Reference Guide</h1>

---

###### _Checklist:_  

- Is easy to find the Reference Guide clearly visible on the main page
- Is the Reference Guide searchable or at least visually easily able to be scanned
- All items are described in clear language, no-jargon language
- Options and defaults are explained and linked to more information where appropriate
- Think of as a Dictionary/Cookbook for Project
- Meant to be easily searchable not to be read front to back
- Try to make terms searchable
- Try to make it easy to scan
- Is every single thing covered?
	-  Terms  
	-  Functions
	-  Arguments
	-  Parameters
	-  Defaults
	-  Datasets or items included in the package
	-  Buttons (in the case of a GUI)
- Good things to do
	- define item
	- tells how relates to other items link to that item when possible
	- what are the inputs and when are these inputs needed
	- what are the defaults
	- show usage in context i.e., show the code
	- avoid jargon
- Consistent Entry Format
	- Consistency is key
	- All entries in the reference guide should have the same info in, the same order
	- Note: Where the package is ending up might define the format 
- Data Formats Defined
	- Project should use data formats that are common
	- If using non-standard data formats then the document needs to explain the specific requirements 
		- Include files for positive/negative/example
		- Have a tool that the end-user can convert the standard format into your format, even better have this be part of the Project
	- Good Example:
		- [GSEA has great descriptions of their data formats](https://www.gsea-msigdb.org/gsea/doc/GSEAUserGuideTEXT.htm#_Loading_Data) with examples of what the data formats look like.

---

## Command Line Tool Items

  - All functions are described
  - All arguments of those functions are described
  - All parameters are described and defaults explained
  - Any additional datasets or items included in the package are documented
  - Any input file formats are described (example file format included is ideal)
  - Any output file formats are described
  - If help is command line package then make sure what command needs to be used i.e. --help

----

## GUI Tool Items

  - All buttons are described
  - All parameters are described and defaults explained
  - Any input file formats are described (example file format included is ideal)
  - Any output file formats are described

---

## Cheat Sheet ideas:

For inspiration and examples of nice cheat sheets, take a look through [RStudio's cheat sheets](https://www.rstudio.com/resources/cheatsheets/)

If you use Overleaf, there are [template cheat sheets you can use here](https://www.overleaf.com/gallery/tagged/cheat-sheet).

---

## Accessibility 

- [Accessibility](Template - Accessibility Information.md)

---

## Good Examples
- [DESeq2’s reference guide](https://bioconductor.org/packages/release/bioc/manuals/DESeq2/man/DESeq2.pdf)
- [GSEA has great descriptions of their data formats](https://www.gsea-msigdb.org/gsea/doc/GSEAUserGuideTEXT.htm#_Loading_Data) with examples of what the data formats
- Bioconductor packages 
	- have [specific guidance on these reference manuals](http://cran.fhcrc.org/doc/manuals/R-exts.html#Documenting-functions)
	- [typically look like this](https://bioconductor.org/packages/3.12/bioc/manuals/GenomicRanges/man/GenomicRanges.pdf) or [this](https://bioconductor.org/packages/3.12/bioc/manuals/GenomicRanges/man/GenomicRanges.pdf)
- Follow the advice from Hadley Wickham from the [R Packages book](https://r-pkgs.org/man.html) which includes using [roxygen2 package](https://cran.r-project.org/web/packages/roxygen2/vignettes/roxygen2.html) to automatically render those .Rd files!
- _For Python package documentation:_ Follow the `docstrings` guidance and instructions [here](https://realpython.com/documenting-python-code/)






---
_Add Your Contact Information_
<center>Yvonne M. Beine FitzGerald | [theYvonne.com](https://theyvonne.com) | hi[@]theyvonne.com </center>  

_Add Links To Your Info_

<center>Terms | Privacy Policy | Project </center>

<center>Lasted Update: 17 July 2022 </center>



