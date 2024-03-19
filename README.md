# NOAA Fisheries PAM-SI Meeting, March 2024

This repository consists of documents related to the NOAA Fisheries Passive Acoustic Monitoring Strategic Initiative Meeting in March 2024 at Southwest Fisheries Science Center in La Jolla, CA.

## **How to Cite** \[TBD\]

## **Contents**

The meeting report is in Quarto Book format; this repository is based on the [NOAA Tech Memo template](https://github.com/nmfs-opensci/NOAA-tech-memo-template) provided by Eli Holmes.

This directory contains:

\[*add link to folder on github for each of these tabs, this is a preliminary organization- may modify as report evolves. Also, in trying to clean out some of the unnecessary template info, I have created a 'delete' folder in many places. These will contain items I hope to delete from each folder. Just in case they create problems with the rendered output-- I'll keep them there for now. Once we know we can render our project well, then we can delete the delete folders!*\]

-   README.md: Read me Instructions for the front page of the Repository.

-   index.qmd: *Engine for rendering project.*

-   \_quarto.yml: *Primary* *formatting for Report.*

-   \_frontmatter.yml: *Aesthetic formatting for Report*

-   .gitignore: *Identify items on local project repo that should NOT be pushed up to github*

-   📁 text: Report pages

-   📁 data: Contains all input data (and metadata) used in this report. (*I do not think we will have data, so we may delete this!*)

-   📁 images: images used in document formatting

-   📁 info: Any miscellaneous background information not directly used in the report (deliverables, reporting requirements, etc)

-   📁 docs: Contains rendered versions of the reports

-   📁 notes: Meeting notes and summaries

-   📁 presentations: Meeting Presentations

-   📁 scratch: random temporary items; entire folder can be deleted when final report is published.

-   📁 functions: scripts that actually do things. Please label explicitly and comment heavily!

-   📁 tex

-   📁 Other stuff- came with the template!

## Discussions

\[link to discussions\]

## R package dependencies

The package dependencies are defined in the DESCRIPTION file. You can check if you have all the required dependencies and install if necessary, via

```         
devtools::install_deps()
```

You run this from the base level, i.e. your working directory is where the DESCRIPTION file is. Install the {devtools} package first if you don't have it installed.

As you work on your project, add any packages your documents require to the DESCRIPTION file. That way users can quickly install dependencies. A easy way to analyze your project code and find any dependencies is using the {renv} package. You don't need to use {renv}; you can just use it's utility for analyzing all your code. It starts at the base directory and works downward.

```         
renv::dependencies()
```

<hr>

## Disclaimer

This repository is a scientific product and is not official communication of the National Oceanic and Atmospheric Administration, or the United States Department of Commerce. All NOAA GitHub project content is provided on an 'as is' basis and the user assumes responsibility for its use. Any claims against the Department of Commerce or Department of Commerce bureaus stemming from the use of this GitHub project will be governed by all applicable Federal law. Any reference to specific commercial products, processes, or services by service mark, trademark, manufacturer, or otherwise, does not constitute or imply their endorsement, recommendation or favoring by the Department of Commerce. The Department of Commerce seal and logo, or the seal and logo of a DOC bureau, shall not be used in any manner to imply endorsement of any commercial product or activity by DOC or the United States Government.

## License addendum

Software code created by U.S. Government employees is not subject to copyright in the United States (17 U.S.C. §105). The United States/Department of Commerce reserve all rights to seek and obtain copyright protection in countries other than the United States for Software authored in its entirety by the Department of Commerce. To this end, the Department of Commerce hereby grants to Recipient a royalty-free, nonexclusive license to use, copy, and create derivative works of the Software outside of the United States.
