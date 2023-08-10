---
permalink: /
title: "Junjie Fei's Homepage"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a research assistant at the Department of Computer Science and Engineering, Southern University of Science and Technology (SUSTech). Before that, I obtained my BS and MS degrees from Chongqing University (CQU) and Xiamen University (XMU), respectively.

My recent research intersts lie in vision-language multimodal learning and artificial intelligence generated content.

I am currently actively searching for a PhD position, drop me an email if you are interested.

News
======
* [2023/07/14] 1 paper has been accepted by ICCV 2023!
* [2023/04/07] Project [*Caption Anything*](https://github.com/ttengwang/Caption-Anything) is publicly released!

Research
======
<tr onmouseout="iadsurvey_stop()" onmouseover="iadsurvey_start()">
  <td style="padding:20px;width:25%;vertical-align:middle">
      <div class="one">
      <img src='images/ViECap.jpg' width="160">
      </div>
      <script type="text/javascript">
      function iadsurvey_start() {
          document.getElementById('iadsurvey_image').style.opacity = "1";
      }
      function imiad_stop() {
          document.getElementById('iadsurvey_image').style.opacity = "0";
      }
      imiad_stop()
      </script>
  </td>
  <td style="padding:20px;width:75%;vertical-align:middle">
      <a href="https://arxiv.org/pdf/2307.16525.pdf">
      <papertitle>Transferable Decoding with Visual Entities for Zero‑Shot Image Captioning</papertitle>
      </a>
      <br>
      <strong>Junjie Fei*</strong>, Teng Wang*, Jinrui Zhang, Zhenyu He, Chengjie Wang, Feng Zheng
      <br>
      <em>ICCV</em>, 2023
      <br>
      <a href="https://github.com/FeiElysia/ViECap">code</a>
      /
      <a href="https://arxiv.org/pdf/2307.16525.pdf">paper</a>
      <p></p>
      <p>
      Improve the generalization by overcoming the hallucination problem in LLMs-based visual models.
      </p>
  </td>
</tr>

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
