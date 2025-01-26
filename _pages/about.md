---
permalink: /
title: "About Me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
I am a Postdoctoral Research Associate in the [Department of Computing](https://www.imperial.ac.uk/computing/) at [Imperial College London](https://www.imperial.ac.uk/). Prior to this, I earned my PhD at [Imperial College London](https://www.imperial.ac.uk/), supervised by [Prof. William J. Knottenbelt](https://www.doc.ic.ac.uk/~wjk/). Previously, I obtained my Master’s degree, advised by [Prof. Qianhong Wu](https://scholar.google.com/citations?hl=en&user=eEzaPPYAAAAJ), and my Bachelor’s degree from [Beihang University](https://ev.buaa.edu.cn/).


<!-- advised by [Prof. Qianhong Wu](https://scholar.google.com/citations?hl=en&user=eEzaPPYAAAAJ), and  from École Centrale de Pékin, Beihang University.   -->

My research interests encompass privacy and security challenges in computer systems, with a particular focus on cryptography, blockchain, and their practical applications. Currently, I am exploring the following topics:

- <span style="font-size:0.9em;"> Blockchain privacy, security, consensus, and applications </span>
- <span style="font-size:0.9em;"> Applied cryptography, including classical and post-quantum solutions</span>
- <span style="font-size:0.9em;"> Decentralized Artificial Intelligence (DeAI)</span>

<!-- Please feel free to reach out to me at <u>zhipeng.wang20[at]imperial.ac.uk</u> if you are interested in my research or would like to know more about my detailed CV. -->


Selected Publications
=======
Full publication list can be found at [Google Scholar](https://scholar.google.com/citations?hl=en&user=ughaML4AAAAJ&view_op=list_works&sortby=pubdate).

- <span style="color:green">\[CT-RSA'25\]</span> [DSKE: Digital Signatures with Key Extraction.](https://eprint.iacr.org/2022/1753.pdf)<br />
**Zhipeng Wang**, Orestis Alpos,  Alireza Kavousi, Harry W. H. Wong, Sze Yiu Chau, Duc V. Le, Christian Cachin.<br /> 
Accepted at The Cryptographers' Track at RSA Conference 2025 (CT-RSA'25). <br /> 



- <span style="color:red">\[WWW'23\]</span> [On How Zero-Knowledge Proof Blockchain Mixers Improve, and Worsen User Privacy.](https://arxiv.org/pdf/2201.09035.pdf)\
**Zhipeng Wang**, Stefanos Chaliasos, Kaihua Qin, Liyi Zhou, Lifeng Gao, Pascal Berrang, Ben Livshits, Arthur Gervais.\
The 2023 ACM Web Conference 2023 (WWW 2023). 

- <span style="color:red">\[S&P'23\]</span> [SoK: Decentralized Finance (DeFi) Attacks.](https://arxiv.org/pdf/2208.13035.pdf)<br />
Liyi Zhou, Xihan Xiong, Jens Ernstberger, Stefanos Chaliasos, **Zhipeng Wang**, Ye Wang, Kaihua Qin, Roger Wattenhofer, Dawn Song, Arthur Gervais.<br />
The 44th IEEE Symposium on Security and Privacy (S&P 2023).

- <span style="color:green">\[FC'22\]</span> [Speculative Multipliers on DeFi: Quantifying On-Chain Leverage Risks.](https://link.springer.com/chapter/10.1007/978-3-031-18283-9_3)<br />
**Zhipeng Wang**, Kaihua Qin, Duc Vu Minh, and Arthur Gervais.<br />
Financial Cryptography and Data Security 2022 (FC 2022).



- <span style="color:darkgray">\[NeurIPS DMLW'22\]</span> [FLock: Defending Malicious Behaviors in Federated Learning with Blockchain.](https://arxiv.org/pdf/2211.04344.pdf)<br /> 
Nanqing Dong<sup>*</sup>, Jiahao Sun<sup>*</sup>, **Zhipeng Wang**<sup>*</sup>, Shuoying Zhang<sup>*</sup>, and Shuhao Zheng<sup>*</sup>.<br /> 
NeurIPS 2022 Workshops on Decentralization and Trustworthy Machine Learning in Web3: Methodologies, Platforms, and Applications. [Runner-up Award.](https://ai-secure.github.io/DMLW2022/papers)<br />
<sup>*</sup>Authors are arranged in alphabetical order.

- <span style="color:darkgray">\[ProvSec'19\]</span> [A Practical Lattice-Based Sequential Aggregate Signature.](https://link.springer.com/chapter/10.1007/978-3-030-31919-9_6)<br />**Zhipeng Wang**, Qianhong Wu.<br />
International Conference on Provable Security 2019 (ProvSec 2019).


<!-- {% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %} -->





<!-- Getting started
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
More info about configuring academicpages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful. -->
