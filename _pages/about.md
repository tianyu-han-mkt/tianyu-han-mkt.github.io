---
permalink: /
title: # "About"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
  - /home/
---

Welcome!

I am an Assistant Professor of Marketing at [HKUST Business School](https://mark.hkust.edu.hk/). I obtained my PhD from UC Berkeley. My research studies behavioral economics and marketing using a combination of field experiments and surveys, causal inference for observational studies, structural modeling, and machine learning. 

Email: <img src="/images/email.png" alt="Email" width="160"/>
<!-- ![email](/images/email.png) -->

Working Papers
-----
"Rewards and Consumption in the Credit Card Market" ([draft](https://ssrn.com/abstract=4497019))
<details>
<summary>Abstract</summary>
<br>
Reward programs are often a prominent feature of credit cards. Collaborating with a leading bank in China, I combine proprietary consumer-level data and a survey to study the causal effect of rewards on consumption and consumers' subjective expectations. I leverage a fuzzy regression discontinuity (RD) design to show that a more generous reward design causes consumption increases across both reward-earning and non-reward-earning categories. Applying the fuzzy RD to the survey data, I find that consumers correctly anticipate the impact of reward design on reward-earning consumption but underestimate its effect on total consumption. Using a stylized model, I study the implications of this misperception for market structure and welfare. My calibration results show that consumer misperceptions incentivize banks to offer more generous rewards, which ultimately diminishes market efficiency and leads to a cross-subsidy from less to more sophisticated consumers.
<br>
<img src="/images/reward-rd.png" alt="Reward Effect using Fuzzy RD" width="800"/>
</details>
<br/>

"An Empirical Model of Endogenous Attention," with T. Tony Ke and J. Miguel Villas-Boas (draft available upon request)
<details>
<summary>Abstract</summary>
<br>
Before making a choice, individuals can gradually gather information on multiple different possible alternatives. Analysts may observe how long the individuals gather information on each alternative, when individuals switch from  gathering information on one alternative to gathering information on another alternative, and when individuals make a final choice. We develop an empirical model on this choice process, endogenizing the choice of which alternative the individual obtains information from at each point in time, and estimate the model with data from eye-tracking experiments. The empirical analysis yields estimates of the relative size of search costs, switching costs, and informativeness of search for information. Counterfactual analysis shows that higher switching costs reduce search duration and induce fewer attention switches; in comparison, higher search costs also reduce search duration but induce more attention switches. The model also delivers that there is a positive correlation between attention to an alternative and likelihood of that alternative being chosen, through the individuals choosing to learn more about the alternatives for which the individuals have beliefs of a higher preference. 
<br>
<img src="/images/search-mdp.png" alt="Optimal Search Policy" width="800"/>
</details>
<br/>

"Interest Rate Misperception in the Credit Card Market," with Xiao Yin ([draft](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4256372) new as of March 2024!)
<details>
<summary>Abstract</summary>
<br>
We investigate the extent to which consumers misperceive the interest costs associated with credit card debt using a combination of administrative data and surveys. Through a randomized controlled trial with an information treatment, our results show that consumers are imperfectly informed about the interest cost of unsecured debt, and the resulting misperception induces excess debt-taking by 26\%, mainly originating from spending on luxury goods. To understand the formation of interest rate misperception, we uncover selective information acquisition to be a potential channel. We demonstrate that consumers tend to actively seek information about their borrowing status when they expect creditworthiness to be high, and they disproportionately pay more attention to favorable information when interest rates are low. 
<br>
<img src="/images/debt-bias.png" alt="Interest Rate Misperception and Debt" width="400"/>
<img src="/images/pr_revision.png" alt="Perceived Interest Rate Revision" width="400"/>
</details>
-----

Work in Progress
-----

"Income Misreporting in the Credit Card Market," with Xiao Yin (draft coming soon)
<details>
<summary>Abstract</summary>
<br>
(Preliminary) In the process of acquiring credit cards, consumers often self-report their income levels, a practice that tends to be prone to unverified overstatements. We empirically investigate into the existence of such income misrepresentation and assess whether financial institutions take this potential exaggeration into account. Collaborating with a leading commercial bank in China, we survey consumers on their income growth rates. By utilizing these reported growth rates and current incomes, we infer the consumers' actual income at the time of their credit card application. Our findings indicate a significant degree of income over-reporting among consumers, with an average exaggeration of approximately 30%. Further, we employ a quasi-experimental approach to determine the causal effect of this income misreporting on the allocation of credit limits. Our results suggest that the bank does, in fact, take into account such misreporting behaviors: income exaggerated by 10% decreases credit limit by around 100 US dollars. This study provides insights into consumer behaviors in credit card applications and the corresponding response of financial institutions.
<br>
<img src="/images/income.png" alt="Event Study" width="400"/>
</details>
<br/>


<!-- This is the front page of a website that is powered by the [academicpages template](https://github.com/academicpages/academicpages.github.io) and hosted on GitHub pages. [GitHub pages](https://pages.github.com) is a free service in which websites are built and hosted from code and data stored in a GitHub repository, automatically updating when a new commit is made to the respository. This template was forked from the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/) created by Michael Rose, and then extended to support the kinds of content that academics have: publications, talks, teaching, a portfolio, blog posts, and a dynamically-generated CV. You can fork [this repository](https://github.com/academicpages/academicpages.github.io) right now, modify the configuration and markdown files, add your own PDFs and other content, and have your own site for free, with no ads! An older version of this template powers my own personal website at [stuartgeiger.com](http://stuartgeiger.com), which uses [this Github repository](https://github.com/staeiou/staeiou.github.io).

A data-driven personal website
======
Like many other Jekyll-based GitHub Pages templates, academicpages makes you separate the website's content from its form. The content & metadata of your website are in structured markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over -- just be sure to save the markdown files! Finally, you can also write scripts that process the structured data on the site, such as [this one](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://academicpages.github.io/talkmap.html).

Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this repository](https://github.com/academicpages/academicpages.github.io) by clicking the "fork" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/_files/example.pdf.  
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
