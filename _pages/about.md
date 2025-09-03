---
permalink: /
title: "Academic Pages is a ready-to-fork GitHub Pages template for academic personal websites"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Welcome to my website. This is a project I started in August 2025 with the goal of building a central place to document and share my research portfolio. It includes past and present projects, ideas for the future, and even a section for stories and personal bits [here](https://jdavidpoling.github.io//year-archive/).

Who Am I?
======
I am an American Marine Scientist currently based in Southern Norway, where I am doing my PhD with the University of Agder in [Coastal Ecology](https://www.uia.no/english/research/phd-programmes/index.html) and have an office at the IMR [Flødevigen Research Station](https://www.hi.no/en/hi/laboratories/flodevigen-research-station). My masters' is in Coastal Environmental Management from Duke University where I worked with Dave Johnston and the Marine Robotics and Remote Sensing [(MaRRS) Lab](https://marineuas.net/new/). My bachelors is in Marine Science with a minor in Applied Ecology from North Carolina State University where I did my bachelors thesis with Ryan Paerl's [Microbial Ecology Lab](https://paerllab.wordpress.ncsu.edu/). 

PhD Work
======
My PhD work focuses on the development of machine learning methods for studying marine fauna. This includes development of new models and ML-based workflows to analyze remote underwater video (BRUV/RUV) as well as working with fish indivudal re-identification for coastal cod. I am also leading a visual survey of Raet National Park here in Southern Norway looking at the effects of bottom trawling. 

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one Markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a Markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each Markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

The repository includes [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual Markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the Markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and Markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a Markdown file for a talk
![Editing a Markdown file for a talk](/images/editing-talk.png)

Want to Chat?
------
If you have a specific question or would like to chat anything marine science or remote sensing, you can reach me at any of the links on the left hand of this page (below my face). My university email is where you will likely get the quickets response. If your question directly relates to any of my projects on GitHub you can also leave a note in "Issues" or "Discussions" in those repositories.
