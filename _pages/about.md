---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
Hello! I am currently a doctoral student from School of Mathematical Sciences, [Peking University](https://english.pku.edu.cn/), advised by [Prof.Heng Mao](https://www.math.pku.edu.cn/teachers/maoh/index.html). I got my B.Eng degree in Sept. 2019, from Department of Optoelectronic Science and Technology, [Harbin Institute of Technology](http://en.hit.edu.cn/). 

I have an undergraduate background in optoelectronic instruments and received extensive training in constructing optical imaging instruments during my Ph.D research. Additionally, my studies in the mathematics department has enhanced my ability to solve interdisciplinary problems using computational imaging techniques. Currently, I focus on breaking imaging limitations in biomedical imaging through advanced optical and mathematical computation approaches.

Research Interests
======
<ul>
  <li><strong>Advanced Methods in High-resolution Microscopy</strong></li>
  <li><strong>High dimensional Zebrafish Brain imaging</strong></li>
</ul>

Research Projects
======
During my Ph.D's research, I participated in and led several research projects. My work and contributions are as follows.

Computational Imaging in Label-free Microscopy
------
In order to address the problems of time-consuming scanning and throughput limitation in the cell microarray, I developed a high-throughput and high-content array screening imaging system. By customizing an ultra-high throughput objective lens, it achieved more than four times the imaging throughput of commercial high-throughput objective lenses. And I further improved the imaging throughput by utilizing Fourier ptychography microscopy (FPM). In addition, I have developed a structured illumination super-resolution imaging modality (SIM) based on the system. The whole system achieves both label-free and fluorescence modalities for living cells and tissue samples, allowing for comprehensive study of their structures and functions. This work has been published, <strong>Liang Chen</strong>, et al., <i>Optics and Lasers in Engineering</i> [DOI](https://doi.org/10.1016/j.optlaseng.2024.108055).

<strong> Key words </strong>: Label-free microscopy, High-throughput imaging, Fourier ptychography microscopy, High SBP objective lens, System calibration

<strong> Funding </strong>: National Major Research Instrumentation Program, National Natural Science Foundation in China (<strong>NSFC, Grant No.81827809</strong>), to develop a high-throughput and high-content array screening and imaging system for self-assembled cell Microarray, participant.

<strong> Advisor </strong>: [Prof.Heng Mao](https://www.math.pku.edu.cn/teachers/maoh/index.html), [Prof. Jianzhong Xi](http://www2.coe.pku.edu.cn/subpaget.asp?id=19)

光路图，系统图，软件截图，结果图
---
title: "Portfolio item number 1"
excerpt: "Short description of portfolio item number 1<br/><img src='/images/500x300.png'>"
collection: portfolio
---

Lightsheet Microscopy in Zebrafish Brain Imaging
------
asa

A Two-photon Screening Platform for Fluorescent Protein
------
asa

Adaptive Optics (AO) in Microscopy 
------
aaa

Teaching Experiences
======
1. <strong>Digital Image Processing</strong>, Spring Semester 2023, teaching assistant
2. <strong>Bioinformatics Methods and Applications</strong>, Fall Semester 2022, teaching assistant
3. <strong>The Design and Analysis of Algorithm</strong>, Fall Semester 2021, teaching assistant
4. <strong>Digital Signal Processing</strong>, Fall Semester 2020, teaching assistant

Publications
======
adasd

Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this repository](https://github.com/academicpages/academicpages.github.io) by clicking the "fork" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

I have also created [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
