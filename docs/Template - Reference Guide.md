<h1 align="center">Reference Guide</h1>

---

###### _This section's checklist:_  

- [ ] Is easy to find: clearly visible on the main page
- [ ] Is searchable or at least visually easily able to be scanned
- [ ] All items are described in clear language
- [ ] Provide items in a clear, no-jargon language
- [ ] Options and defaults are explained and linked to more information where appropriate


#### Command line tool items

  - [ ] All functions are described
  - [ ] All arguments of those functions are described
  - [ ] All parameters are described and defaults explained
  - [ ] Any additional datasets or items included in the package are documented
  - [ ] Any input file formats are described (example file format included is ideal)
  - [ ] Any output file formats are described



#### GUI tool items

  - [ ] All buttons are described
  - [ ] All parameters are described and defaults explained
  - [ ] Any input file formats are described (example file format included is ideal)
  - [ ] Any output file formats are described

---

## Cheatsheet ideas:

For inspiration and examples of nice cheatsheets, take a look through [RStudio's cheatsheets](https://www.rstudio.com/resources/cheatsheets/)

If you use Overleaf, there are [template cheatsheets you can use here](https://www.overleaf.com/gallery/tagged/cheat-sheet).

---


From class notes


#### Creating Reference Guides

#### The Goal of a Reference Guide
- Think of as a dictionary for Tool/App
- Meant to be easily searchable not to be read front to back

#### Characteristics of a Good Reference Guide
- ###### Easy To Find
	- End User can find
	- It is part of the navigation system of help documentation main links
	- If help is command line package then make sure what command needs to be used  ie `--help`
- ###### Easy To Search
	- End User are looking for something specific, the document should be searchable or at least alphabetical.  
	- Try to make terms searchable
	- Try to make it easy to scan
- ###### Comprehensive
	- Is every single thing covered?
		- Terms
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
		- show usage in context I.e. show the code
		- avoid jargon
	- ###### Data Formats Defined
		- Tool/App should use data formats that are common
		- If using non-standard data formats then the document needs to explain the specific requirements 
			- Include files for positive/negative/example
			- Have a tool that the end-user can convert the standard format into your format, even better have this be part of the Tool/App
		- [GSEA has great descriptions of their data formats](https://www.gsea-msigdb.org/gsea/doc/GSEAUserGuideTEXT.htm#_Loading_Data) with examples of what the data formats look like.
	- ###### Consistent Entry Format
		- Consistency is key
		- All entries in the reference guide should have the same info in, the same order
		- Note where the package is ending up might define the format
			- For example Bioconductor  packages have [specific guidance on these reference manuals](http://cran.fhcrc.org/doc/manuals/R-exts.html#Documenting-functions)


- #### Example Good Reference Guide Doc 
	- [DESeq2’s reference guide](https://bioconductor.org/packages/release/bioc/manuals/DESeq2/man/DESeq2.pdf), Love, Huber, and Anders ([2014](https://jhudatascience.org/Documentation_and_Usability/no_toc/creating-handy-reference-guides.html#ref-Love2014)
	- [GSEA has great descriptions of their data formats](https://www.gsea-msigdb.org/gsea/doc/GSEAUserGuideTEXT.htm#_Loading_Data) with examples of what the data formats look like.
	- Bioconductor packages 
		- have [specific guidance on these reference manuals](http://cran.fhcrc.org/doc/manuals/R-exts.html#Documenting-functions)
		- typically look like this [https://bioconductor.org/packages/3.12/bioc/manuals/GenomicRanges/man/GenomicRanges.pdf](https://bioconductor.org/packages/3.12/bioc/manuals/GenomicRanges/man/GenomicRanges.pdf)




####  Week 3 - 2 Exercise: Create your own reference guide![](https://jhudatascience.org/Documentation_and_Usability/no_toc/creating-handy-reference-guides.html#exercise-create-your-own-reference-guide)
###### R package documentation
- Follow the advice from Hadley Wickham from the [R Packages book](https://r-pkgs.org/man.html) which includes using [roxygen2 package](https://cran.r-project.org/web/packages/roxygen2/vignettes/roxygen2.html) to automatically render those .Rd files!

###### Bioconductor
- If your tool’s destination is Bioconductor, see their specific guidance on [manual pages](https://bioconductor.org/developers/package-guidelines/#manpages).

###### Python
- _For Python package documentation:_ Follow the `docstrings` guidance and instructions [here](https://realpython.com/documenting-python-code/)

###### General Purpose
- you can our [the reference guide template](https://raw.githubusercontent.com/jhudsl/template-documentation/master/docs/reference_guide_template.md) to start your own reference guide either by using the markdown template directly, or navigating to the MkDocs repository you set up in the previous chapter.



---

## Versions History

- 21 May 2022
	- Used documeent from the Cousera Class Documentation and Usability for Cancer Informatics by John Hopkins University	as baseline
	- Added additional items and customized to become my standard template for creating Tool/App Documentation


---
_Add Tool/App Contact Info_
<center>Yvonne M. Beine FitzGerald | [theYvonne.com](https://theyvonne.com) | hi[@]theyvonne.com </center>  

_Add Links_

<center>Terms | Privacy Policy | App/Tool </center>

<center>Lasted Update: 26 June 2022 </center>


