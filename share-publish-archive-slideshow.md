## Share, publish, & archive research products

authors: <a href="https://github.com/Reproducible-Science-Curriculum/rr-publication" target="_blank">Reproducible Science Curriculum contributors</a>, modified by NEON staff


## Reproducibility Is Beneficial

* To us as scientists
* To the scientific community


##

> [Five selfish reasons to work reproducibly](http://www.genomebiology.com/2015/16/1/274) - Florian Markowetz

1. Reproducibility helps to avoid disaster
2. Reproducibility makes it easier to write papers
3. Reproducibility helps reviewers see it your way
4. Reproducibility enables continuity of your work
5. Reproducibility helps to build your reputation

## Share vs. Publish vs. Archive

**Sharing, Publishing, & Archiving are not the same things**

## Share

> _SHARE_: any way of sharing information -- could mean I emailed it to you


## Publish

> _PUBLISH_: The data / code are citable & discoverable

## Archive

> _ARCHIVE_: Long-term preservation -- there is a long term plan to store
(and provide access to) the data / code

## Publish & Archive

In this presentation, we'll focus on publishing & archiving

## Common Questions

* Why publish?
* Who are we sharing with?
* What materials do we need to publish?
* When do we make them available?
* Where do we publish various outputs?
* How do we prepare materials for publication?

##

Let's assume that we are at the point of submitting our manuscript

## Why Publish?

* Increased visibility / citation
* Funding agency / journal requirement
* Community expects results from funded projects


## Increased visibility / citation


<div class="column column1">
<figure>
  <img src="images/share-publish-archive/PiwowarVision_2013_PeerJ_Fig1.png" width="90%" alt="Baby Orang Utan hanging from a rope">
</figure>
</div>
<div class="column column2">
<small> Figure 1: Citation density for papers with and without publicly available
microarray data, by year of study publication. </small>
Source: [Piwowar & Vision. 2013. Data reuse and the open data citation advantage](https://dx.doi.org/10.7717/peerj.175)
</div>

## Requirements Can Vary

* **FUNDING AGENCIES:**  
    - [NSF Dissemination and Sharing of Research Results policy](http://www.nsf.gov/bfa/dias/policy/dmp.jsp)
    - [NIH Data Sharing policy](http://grants.nih.gov/grants/policy/data_sharing/)
* **JOURNALS:**
    - [PLOS Publishing policies](http://journals.plos.org/plosone/s/editorial-and-publishing-policies)
    - [Nature Publishing policies](http://www.nature.com/authors/policies/availability.html)

## Why Publish / Share?

* Increased visibility / citation
* Funding agency / journal requirement
* Community expects it
* _Better research_
* _More efficient, less redundant science_
    - Others can more effectively build upon your work

## Why Share? Better Research.

<div class="column column1">
![](http://journals.plos.org/plosone/article/figure/image?size=large&id=info:doi/10.1371/journal.pone.0026828.g001)
</div>

<div class="column column2">
Figure 2: Distribution of reporting errors per paper, for papers from which data
were shared and from which no data were shared.

<small>Source: [Wicherts et al. 2011. Willingness to Share Research Data Is Related to the Strength of the Evidence and the Quality of Reporting of Statistical Results.](http://dx.doi.org/10.1371/journal.pone.0026828)</small>
</div>

## Who do we need to share with?

>For research to be reproducible, the research products (data, code) need to be
publicly available in a form that people can find and understand them.

* Collaborators
* Peer reviewers & journal editors
* Broad scientific community
* General public

## What Should We Share?

**Consider a recent project or paper of yours:**

- Which parts are important to publish?
- Which parts are less important to publish?
- Which parts are too sensitive / cannot be published?


## Things We Should Publish

* Starting data set (if it's not already available)
* Metadata
* Data cleaning steps
* Analysis scripts
* Source code
* Readme


## Things We Should May or May Not Publish

* Raw data: especially if it's already available
* Processed / cleaned data
* Intermediate results

## Things We Shouldn't Publish

* Confidential (e.g., patient) data
* Material already published
* Pre-existing restrictive license
* Passwords, private keys


## How To Decide What to Publish

> Pro-Tip: Re-run your analyses: Make all of the data, code & notes needed  to
run your analysis, available.

[Computing Workflows for Biologists: A Roadmap](http://journals.plos.org/plosbiology/article?id=10.1371/journal.pbio.1002303)

## When Should I Publish?

> You can make your code and data public at any point of the research process.
When you submit a paper, results should be
reproducible and data & code should be published.

## When Should I Publish?

* Journals often require code publication
    - Allows editors & reviewers to accurately review methods
    - You can often publish code for reviewers only to be publicly released when the paper is published

## Where Should I Publish?

* Domain-specific data repository (GenBank, PDB)
* Source code hosting service ([GitHub](http://github.com), [Bitbucket](http://bitbucket.com))
* Generic repository ([Dryad](http://datadryad.com), [figshare](http://figshare.com), [Zenodo](http://zenodo.org))
* Institutional repository
* Sharing services ([RPubs](http://rpubs.com), [iPython Notebook Viewer](http://nbviewer.ipython.org/), Dropbox, Google Drive)

## Many repositories

[Registry of Research data Repositories](http://re3data.org)

> Pro_tip: Archival Repository is one that retains your
data for a set period of time. Funding agencies often have requirements associated
with duration of the archive.

## How to Chose a Repository

* Is there a domain specific repository?
* What are the backup & replication policies?
* Is there a plan for long-term preservation?
* Can people find your materials?
* Is it citable? (does it provide DOIs)
* Is your purpose archival, sharing or publication?

## Where to Publish Various Parts of a Project

**You will likely have different project components:**

* R Markdown, Jupyter notebook, etc.
* Source code
* Other documentation
* Raw data
* Derived data

## Where to Publish Various Parts of a Project

**Example (Python focused) workflow:**

* Develop code: GitHub
* Upon Publication:
    - Share notebooks on GitHub, Notebook Viewer links
    - Archive a snapshot of data in Dryad
    - Code snapshot to Zenodo


## Resources: Libraries Can Help

> Pro-Tip: University and institution libraries often have resources for data
management plans, repository access and data archiving.

Ask a Librarian!

## How to share & publish: standard data formats

> Pro-Tip: Using standard data formats increases opportunities for re-use and
expansion of your research.

## Document Format Considerations

**Do Use:**

* Non-proprietary file formats
* Text file formats (.csv, .tsv, .md, .txt)

**Don't Use:**

* Proprietary file formats (.xls)
* Numeric data in PDFs or images (please, please don't!)
* Data in Word documents

## A Reproducible Project Should Include

* Top-level `README` that describes data / software package
* List files & naming conventions
* Describe abbreviations, column names, etc
* Software installation & usage instructions
    - Create separate `INSTALL` if long
* Citation instructions
    - Consider creating a [`CITATION` file](http://blog.rtwilson.com/encouraging-citation-of-software-introducing-citation-files/)
* Contribution instructions
    - Github will automatically link to `CONTRIBUTING` file for new issues and
    pull requests

## Concerns about publishing data & code

* What are some of the challenges of publishing research
products?
* What are some of the concerns that you may have?
