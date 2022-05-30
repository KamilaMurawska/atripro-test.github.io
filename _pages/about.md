---
permalink: /
title: "academicpages is a ready-to-fork GitHub Pages template for academic personal websites"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Importance of Capping Material Properties in Remediation of Mine Tailings
======
Soil contamination with trace elements in the vicinity of mining sites and smelters poses a serious threat to humans and the environment around the globe. Revegetation of mine tailings to minimize the dispersal of pollutants via wind or groundwater (i.e., phytoremediation) is a promising "green" and low-cost intervention to toxic exposures. Unfortunately, plant growth is inhibited on most tailings, making it necessary to provide additional healthy substrate for seed germination and seedling growth. The current practice is the installation of an uncontaminated soil-gravel-rock cap over the tailings prior to plant seeding, with stockpiles of such material being readily available, a technology known as "cap and plant." However, critical knowledge gaps regarding plant-soil interactions have prevented a broad and efficient implementation of this technology. The primary objective of this project is to identify the optimal strategy for generating a lasting vegetation cover at hazardous mining sites. The guiding hypothesis is that the biophysicochemical properties of capping material are critical for the development of robust root systems that can propagate into the underlying contaminated mine tailings. Using an innovative experimental design, this project is developing specific soil health indices and assessing the effects of capping material depth and quality on root system architecture in a prospective plant species known as saltbush (Atriplex lentiformis) for phytoremediation. Various capping materials from stockpiled overburden and adjacent natural deposits are being tested in three consecutive greenhouse studies that bring together advanced ecological, genomic, and soil health assessments. Specifically, root system development is being monitored using a noninvasive phenotyping method based on rhizotrons, filled with different combinations of capping material and mine tailings from Superfund sites across the U.S. Southwest. Once the optimal soil and plant parameters are identified, possibilities to amend existing but low-quality capping material in a cost-effective way will be explored. This project will yield an unprecedented mechanistic understanding of concurrent changes in plant root system architecture and function in response to the quality and depth of capping materials used for mine tailing restoration. Capitalizing on this knowledge, specific guidelines toward the remediation of hazardous sites will be developed and directly transferred to the mining industry and regulators. As such, the project outcome will be valuable for the economy and society. In addition, the researchers' findings will serve as a global template for mitigating human and environmental health issues in areas affected by mines and smelters.

Experimental design
======
<img src='/images/profile.png'>

1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this repository](https://github.com/academicpages/academicpages.github.io) by clicking the "fork" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

Results
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

I have also created [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the academicpages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring academicpages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
