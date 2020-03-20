README.md
## Grading (95 points + 5 points evals)
## Score: 87/95

1. *Project Scope:*  9

2. *Background and motivation:* 10

3. *Data description:* 9

- what is the time span on the data?

4. *Methodology:* 9

- give overall accuracy of your  decision trees
- what crime levels lead to arrest?

5. *Implementation:* 9

- you split your data but didn't actually use the test data


6. *Discussion/interpretation of results:* 10

7. *Coding style and quality:* 10

8. *Presentation:* 9

- month axis should be relabeled
- day of week should be ordered
- should have proportion not count of stops by race
- use a map to display lat/long data. And reduce the transparency of points since there is a lot of overplotting

9. *Submission:* 10

The following aspects will be graded on a 5-point scale:

10. *Creativity:* 2




Due to some complication caused (at least in part) by COVID-19, Allegra has applied for an extension, but Cameron has not. Therefore, it is important to seperate out whose work is whose.

The website containing the groups work is found here: https://cameronsharpe.shinyapps.io/FinalProject/

A discription of the work done by Cameron before the due date is below (between the -------s)

---------------------

Cameron's contrubution is in CKS.Rmd and Interactive.Rmd (along with their corresponding HTML files). Please grade
that .Rmd file, although note that there are some sections included which were Allegra's part of the project, and are
thus pretty sparse.

A temporary website has been created by Cameron, although the original plan was to have Allegra set that up.

The temporary webiste can be found at: https://sites.google.com/carleton.edu/finalprojectmath285-at-cks/

Note that because of the last minute nature of the set up of the website, not all the graphs are showing up.

A better idea of what the final product should look like is if you actually run CKS.Rmd to turn it into an HTML
document. To simulate this, look at **CKS-markdown.md**, although the shiny interactive graph is obviously missing.

 Be aware that you will need to be signed in to a Carleton College account see this website.
  Also, for some reason the interactive graph is not showing up here. I don't know how to fix this, but the code
  (and HTML file) are both in this github directory.
  
 -----------------

The files in the directory (as written by Cameron when he submitted) are:

  .gitignore: (this is unused) 
  
  2018_sqf_database.csv: the original version of the data set, taken from https://www.nyclu.org/en/stop-and-frisk-data
  
  **CKS.Rmd**:	Cameron Kline-Sharpe's Part of the Submission
  
  CKS.nb.html:	Cameron Kline-Sharpe's Part of the Submission (in html format)
  
  final-project:-AllegraTashjian-CameronKlineSharpe.Rproj	Used by R Markdown to interface with Git
  
  interactive.Rmd:	Cameron Kline-Sharpe's Part of the Submission	 (a placeholder interactive graph)
  
  interactive.nb.html:	Cameron Kline-Sharpe's Part of the Submission	(in html format)
  
  stopFrisk.csv: An edited version of the 2018_sqf_database.csv fie where all "(nulls)" are removed.
  
  CKS-markdown.md: A simulation of the HTML file produced by running CKS.Rmd to an HTML file
  
  CKS-markdown_files: A directory containing images used by CKS-markdown.md
  
  **FinalProject.Rmd:** The Rmd file that contains both Cameron and Allegra's work (GRADE FROM THIS)
  
