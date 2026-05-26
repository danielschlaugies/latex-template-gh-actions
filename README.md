# Overview
This repository serves as a template for LaTeX projects using git version control.
Additionally, the LaTeX project is build automatically using a GitHub Actions workflow and then stored as an artifact.
The LaTeX build is triggered by either commiting to the repository, or manually, by navigating to the *Actions* tab, selecting the *LaTeX build* workflow and clicking *Run workflow* in the top-right of the page.
# Usage Instructions 
Either clone/ fork the repository or just copy the [wofklow file](.github/workflows/build-latex-project.yml) and add necessary changes to it. In particular, specify the LaTeX file(s) in the checkout step and adjust the name of the pdf-file in the upload-artifact step.
# Misc
Also check out, my other project [download-latex-artifact](https://github.com/danielschlaugies/download-latex-artifact), which provides a web application to view the latest generated pdf document in a browser.
