# Comparison of R Markdown and Emacs Org-mode for reproducible reports

## My yak-shavingest project yet

Both R Markdown and Emacs Org-mode provide tools for literate programming and
reproducible reports. I'm interested in comparing them. The plan is to create
the same report using both tools, then evaluate each tool on the success and
ease of accomplishing various components of the project. Things that should be
involved:

* Source blocks and inline code chunks whose output appears in the final document
* Figures (with captions)
* Tables
* Equations
* Citations
* Custom formatting using a LaTeX journal template
* ???

Reproducible reports should be able to be reproduced by people other than their
authors, which means minimizing the number of hoops to get from source to
output. Both the R Markdown and Org-mode reports should be able to be exported
to PDF from the command line; that is, they shouldn't require knowledge of any
particular text editor or IDE. I suspect that some of this will be unavoidable
for the Org-mode document though, and perhaps it is unfair to expect otherwise,
as Org-mode is fundamentally tied to a text editor while R Markdown is not. At
any rate, the less installing and configuring of additional stuff (i.e. the less
[command line bullshittery](http://www.pgbovine.net/command-line-bullshittery.htm)),
the better.
