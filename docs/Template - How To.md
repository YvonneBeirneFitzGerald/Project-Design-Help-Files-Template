<h1 align="center">How To</h1>


---

_Checklist for this section:_

- [ ] Is easy to find: clearly visible on the main page
- [ ] Demonstrates examples that are the most common use case(s)
- [ ] Prerequisite knowledge needed is described
  - [ ] Links to helpful background knowledge resources are included
- [ ] Paste-able or directly runnable code is given and can be run as-is
- [ ] Demonstrates a _reproducible_ example
  - [ ] An example dataset needed is provided and introduced
  - [ ] No additional packages and software are required beyond what is installed in the `Getting Started`
- [ ] Demonstrates step-by-step the most common users for your Tool/App
- [ ] Example code write with teaching in mind
- [ ] Shows what additional analysis might look like

---


## Specific Examples

If your Tool/App's destination is *** XYZ ***, see our specific guidance on those repositories' examples:  

---



# Notes
##### Creating Helpful How-To  Sections
#### Learning Objects
-  Create how-to examples that will increase your users’ familiarity with your tool.
-  Describe components included in useful how-to examples.
-  Understand the goals of how-to examples.
-  Creating handy reference guides


#### Creating Helpful How-To Sections
- Getting Started is for new users
- How To Sections are geared toward intermediate user who want to know more
- Can move someone from moderate interest to raving fan
- Create examples like one would recipes in a cookbook
- Used to show off best use cases for your tool
- some tools/apps call examples different names (Bioconductor = vignettes / I = Snippets)


#### Useful How To Section Characteristics 
##### Focus On End User
- Contains examples of what is most useful to the enduser
- Users do love a full library of how-to examples, but use your time wisely
- Create the most needed examples first

##### Step by Step
- Every step of the process should be given, especially those you take for granted
- Give the exact code needed especially for command-line tools
- Screenshot or video tutorial when the Tool/App is a GUI

#####  Taking Care of The Data 
- If data is needed to run the example make sure it is provided and easy to access when possible give a link to the data source
- If the data needs to be in a certain format make sure this format is included and defined

 ##### Example Code Goal Is To Teach
- Example Code is written to prioritize clarity over cleverness or brevity
- Should have comments
- Don't assume end-users understand conventions
- Should model best practices
- Be consistence with Coding Style and Conventions
- Try to limiting needing other packages and dependencies
	- In a package is required, evaluate if it should automatically install
- Explain how to modify code to end-users needs
- Provide additional resources about options and possibilities
- Review document at the level of a beginner to your Tool/App [Reviewing Your Persona](*** INSERT PERSONAL INFO ***)

##### Tips On Reproducible Code
-   [How to Write a Reproducible Example - Hadley Wickham](https://gist.github.com/hadley/270442#how-to-write-a-reproducible-example)
-   [Making your code reproducible](https://methodsblog.com/2017/12/06/making-your-code-reproducible/)
-   [How to Make a Great R Reproducible Example](https://stackoverflow.com/questions/5963269/how-to-make-a-great-r-reproducible-example)


##### Good Examples How-To 
-  [DESeq2 has excellent vignettes](http://www.bioconductor.org/packages/release/bioc/vignettes/DESeq2/inst/doc/DESeq2.html)! Love, Huber, and Anders ([2014](https://jhudatascience.org/Documentation_and_Usability/no_toc/creating-helpful-how-to-examples.html#ref-Love2014))
- [QIIME2 also has an extensive set of examples](https://docs.qiime2.org/2021.2/tutorials/pd-mice/)! Bolyen et al. ([2019](https://jhudatascience.org/Documentation_and_Usability/no_toc/creating-helpful-how-to-examples.html#ref-Bolyen2019))






---

_For Bioconductor vignettes_:

-   [Our Bioconductor specific how-to example templates](https://jhudatascience.org/template-documentation/bioconductor_guides/bioconductor_vignette_template.Rmd).  
    
-   [Bioconductor’s own vignette guidance](https://www.bioconductor.org/developers/package-guidelines/#Vignettes).  
    
-   [Guidance on writing RMarkdown Vignettes](https://bioconductor.org/packages/devel/bioc/vignettes/BiocStyle/inst/doc/AuthoringRmdVignettes.html) by Andrzej Oleś and Morgan ([2021](https://jhudatascience.org/Documentation_and_Usability/no_toc/creating-helpful-how-to-examples.html#ref-Oles2021)).

_For Galaxy vignettes_:

-   [See this Galaxy tutorial for creating new tutorials!](https://training.galaxyproject.org/training-material/topics/contributing/tutorials/create-new-tutorial/tutorial.html)





from class notes

### Week 3 
##### Creating Helpful How-To  Sections
#### Learning Objects
-  Create how-to examples that will increase your users’ familiarity with your tool.
-  Describe components included in useful how-to examples.
-  Understand the goals of how-to examples.
-  Creating handy reference guides


#### Creating Helpful How-To Sections
- Getting Started is for new users
- How To Sections are geared toward intermediate user who want to know more
- Can move someone from moderate interest to raving fan
- Create examples like one would recipes in a cookbook
- Used to show off best use cases for your tool
- some tools/apps call examples different names (Bioconductor = vignettes / I = Snippets)


#### Useful How To Section Characteristics 
##### Focus On End User
- Contains examples of what is most useful to the enduser
- Users do love a full library of how-to examples, but use your time wisely
- Create the most needed examples first

##### Step by Step
- Every step of the process should be given, especially those you take for granted
- Give the exact code needed especially for command-line tools
- Screenshot or video tutorial when the Tool/App is a GUI

#####  Taking Care of The Data 
- If data is needed to run the example make sure it is provided and easy to access when possible give a link to the data source
- If the data needs to be in a certain format make sure this format is included and defined

 ##### Example Code Goal Is To Teach
- Example Code is written to prioritize clarity over cleverness or brevity
- Should have comments
- Don't assume end-users understand conventions
- Should model best practices
- Be consistence with Coding Style and Conventions
- Try to limiting needing other packages and dependencies
	- In a package is required, evaluate if it should automatically install
- Explain how to modify code to end-users needs
- Provide additional resources about options and possibilities
- Review document at the level of a beginner to your Tool/App [Reviewing Your Persona](*** INSERT PERSONAL INFO ***)

##### Tips On Reproducible Code
-   [How to Write a Reproducible Example - Hadley Wickham](https://gist.github.com/hadley/270442#how-to-write-a-reproducible-example)
-   [Making your code reproducible](https://methodsblog.com/2017/12/06/making-your-code-reproducible/)
-   [How to Make a Great R Reproducible Example](https://stackoverflow.com/questions/5963269/how-to-make-a-great-r-reproducible-example)


##### Good Examples How-To 
-  [DESeq2 has excellent vignettes](http://www.bioconductor.org/packages/release/bioc/vignettes/DESeq2/inst/doc/DESeq2.html)! Love, Huber, and Anders ([2014](https://jhudatascience.org/Documentation_and_Usability/no_toc/creating-helpful-how-to-examples.html#ref-Love2014))
- [QIIME2 also has an extensive set of examples](https://docs.qiime2.org/2021.2/tutorials/pd-mice/)! Bolyen et al. ([2019](https://jhudatascience.org/Documentation_and_Usability/no_toc/creating-helpful-how-to-examples.html#ref-Bolyen2019))


#### Exercise Week 3 - 1 Create your own how-to examples
- Create your own How-To based on the templates from class.


----

## Versions History

- 21 May 2022
	- Inital Document based on the Cousera Class Documentation and Usability for Cancer Informatics by John Hopkins University	
	- Added additional items and customized to become my standard template for creating Tool/App Documentation



---
Yvonne M. Beine FitzGerald  
theYvonne.com  
hi[@]theyvonne.com  

---

Terms (link to Terms Page)  
Privacy (link to Privacy Page)  
App/Tool (bring back to App/Tool Page)  
