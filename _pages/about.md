---
permalink: /
title: "About me "
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hello! I am Daniel Drazhi, an international undergraduate student from [Albania](https://en.wikipedia.org/wiki/Albania) studying Computer Science and Mathematics at the [University of Maine](https://umaine.edu/). At UMaine I have taken a variety of courses from the CS & Math department which have equiped me with the perequisite necessary knowldege to think critically, be a good problem solver, learn new things fast, and succeed in different work roles. I have been engaged as a tutor for several stem courses, volunteered in Machine Learning Research and participated in a Software Engineering internship with CafeX Technologies, a startup based in San Francisco, California. Currently, I am looking for internship positions in Software Engineering, Cybersecurity, Cryptography, Data Science/Machine Learning. Feel free to reach out via the contact information below.  


Contact Information
======
Adress: 1 Hudson St, Orono ME 04473 

Email: daniel.drazhi[@]maine.edu

Mobile: 617-888-4692

For other information such as my Github, Linkedin please look on the left. 


Interests 
======

My outside interests & hobbies are playing soccer, playing chess, reading books and hanging out with people of different backgrounds and cultures. 
I also do have a very strong interest and passion about startups, and what I love mostly about them is the potential to radically change the world for better and improve our lives. A list of my favorite books is provided below. I would love to hear your opinion on any of them and please feel free to reach out with any recommendations. 

1. Outliers: The Story of Success (by Malcolm Gladwell)
2. Meditations (by Marcus Aurelius)
2. Think and Grow Rich (by Napoleon Hill)
3. How to Win Friends and Influence People (by Dale Carnegie)
4. The General of the Dead Army (by Ismail Kadare)
5. The Art of Thinking Clearly (by Rolf Dobelli)
6. Thinking, Fast and Slow (by Daniel Kahneman)
7. Can't Hurt Me: Master Your Mind and Defy the Odds (by David Goggins)
 

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
