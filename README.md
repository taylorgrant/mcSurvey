
<!-- README.md is generated from README.Rmd. Please edit that file -->

# mcSurvey

Code to scrape [Morning Consult](www.morningconsult.com) for all
stories, iterate through all stories looking for pdf crosstabs. Code
then downloads all pdfs, reads in the TOC for each survey, and builds a
table of all questions asked. Survey pdfs are placed in a Box folder and
the TOC is written to an html file that also lives at the Box location.

Take something like this:

![Typical table of contents page](mcimg.png)

And have it look like this

![Typical table of contents page](mcimg2.png)
