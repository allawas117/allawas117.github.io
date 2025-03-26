---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hi! I'm an aspiring software engineer and a recent [University of the Philippines Los Baños](https://uplb.edu.ph/) graduate where I majored in the Mathematics of Reaction Networks. Previously, I was a research associate at the [Institute for Basic Science - Biomedical Mathematics Group](https://www.ibs.re.kr/bimag/) and the [Korea Advanced Institute for Science and Technology (KAIST)](https://www.kaist.ac.kr/en/).


Research Interests
======
1. **Fast AI and Code**. I'm particularly interested in fast AI and algorithmic efficiency, and I'm working on projects that leverage distributed caching to speed things up. While distributed caching can reduce the latency of such algorithms, it can also increase memory usage or network overhead. My research focuses on analyzing these limitations and exploring methods to overcome them.
1. **Mathematical and Computational Biology**. I have conducted research in chemical reaction networks and dynamic network inference for biological systems. Building on this, I am interested in applying fast AI and scalable algorithm design to overcome the challenges of handling large biological datasets.

Industry Interests
======
1. **High-Performance Computing and Scalable Systems**. I am interested in building efficient, scalable software systems that can handle large datasets and real-time processing, especially in the context of AI applications.
1. **Distributed Systems and Cloud Infrastructure**. I am particularly interested in distributed caching, parallelization, and cloud-native architectures that power large-scale AI and data workflows.

Education
======
* University of the Philippines Los Baños (BS Applied Mathematics) - August 2021 to January 2025 

CV
======
See my CV here.

For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

The repository includes [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
