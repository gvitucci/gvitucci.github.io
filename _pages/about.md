---
permalink: /
title: "Home"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hi there!
I'm Giuseppe.
I got my bachelor's degree in engineering physics at the [Politecnico di Torino](https://www.polito.it/), and continued with my specialization in Nanotechnology for ICTs, a joint program between Torino, [INPG Grenoble](https://www.grenoble-inp.fr/) and [EPFL Lausanne](https://www.epfl.ch/en/) . In the last semester I had the opportunity to develop my thesis at the [NASA Jet Propulsion Laboratory](https://www.jpl.nasa.gov/), where I designed and developed a micro-bridge pressure sensor. I also visited California and USA west states (yes, and Las Vegas too. Twice.) and met wonderful people during my stay.

After the graduation, I joined Magneti Marelli as a test engineer for infotainment systems. Despite the interesting opportunity, I soon realized that i wanted to go deeper into my Physics knowledge. That is why I started my PhD in Applied Physics, at the university of [Milano Bicocca](https://www.unimib.it/). I had the possibility to work on a compact microdevice, able to create pictures from neutrons. I conducted most of my experiments at the [RAL](https://www.ukri.org/who-we-are/stfc/locations/rutherford-appleton-laboratory/) laboratories in UK, with some pretty good result, some of which has been published in the official institute site. Do you know what a pearl and a souflè have in common? Well, you can check it [here](https://www.isis.stfc.ac.uk/Pages/Neutron-imaging-study-dives-deep-into-pearls.aspx).

After getting my PhD, I went back to work in a private company, at [Optec](https://www.optec.eu), where i could happily join my career with my evergreen passion for (the Life), the Universe and everything ([citation needed](https://en.wikipedia.org/wiki/Life,_the_Universe_and_Everything)).  I contributed in many space projects, for instance in [LICIA CUBE](https://www.asi.it/en/planets-stars-universe/solar-system-and-beyond/liciacube/) mission.  

After 4.5 "space" years, i decided to change my focus. Following the philosophy of the [School for Poetic Computation](https://sfpc.study/), i wanted to explore a different aspect of my job, trying to merge technical aspects with Art. I am currently at [IGOODI](https://www.igoodi.eu/en/home) , where I am working with compter vision to create realistic digital representations of the real human beautiness.

To sum up, I feel that this plethora of different experiences made me a versatile professional, with a knowledge base spanning multiple disciplines. I like to work in environments that require adaptability and innovative problem-solving. My passion for continuous learning and personal growth drives me to expand my expertise across various domains, making me compfortable in dynamic and evolving industries, where research and development are the watchwords. I will let Herman Melville better explain my thought. He said: "As for me, I am tormented with an everlasting itch for things remote. I love to sail forbidden seas, and land on barbarous coasts."

======
Like many other Jekyll-based GitHub Pages templates, academicpages makes you separate the website's content from its form. The content & metadata of your website are in structured markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over -- just be sure to save the markdown files! Finally, you can also write scripts that process the structured data on the site, such as [this one](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://academicpages.github.io/talkmap.html).

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
