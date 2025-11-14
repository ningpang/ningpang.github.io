---
permalink: /
title: "About Me (庞宁)"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am currently a lecturer at Aviation University of Air Force, China. I obtained my PhD degree under the supervision of Prof. Weidong Xiao and Prof. [Xiang Zhao](https://xiangz-nudt.github.io/) in 2024 at National Univeristy of Defense Technology. I obtained my Master's Degree in 2020 and the Bachelor’s Degree in 2017.

Areas of interest in research include: Knowledge Graph, Large Language Model, World model, Federated Learning and Electromagnetic Warfare.

News
======
One paper is accepted by AAAI 2026.

Selected Publications
======
- `Ning Pang`, Xiang Zhao, Weixin Zeng, Zhen Tan, Weidong Xiao. Towards Privacy-preserving Personalized Federated Relation Classification. IEEE Trans. on Big Data (**TBD**). Early Access, 2025.   

- Simiao Zhao, Zhen Tan, `Ning Pang`, Weidong Xiao, Xiang Zhao. Dynamic-prototype Contrastive Fine-tuning for Continual Few-shot Relation Extraction with Unseen Relation Detection. **COLING**, 2025.

- `Ning Pang`, Xiang Zhao, Weixin Zeng, Zhen Tan, Weidong Xiao. StaRS: Learning a Stable Representation Space for Continual Relation Classification. IEEE Trans. Neural Networks and Learning Systems (**TNNLS**). 2025 36(5):9670-9683. 
[[code]](https://github.com/ningpang/StaRS) 
  
- `Ning Pang`, Xiang Zhao, Weixin Zeng, Zhen Tan, Weidong Xiao. SCL: Selective Contrastive Learning for Data-driven Zero-shot Relation Extraction. Transations of Association for Computational Linguistics (**TACL**). 2024, 12: 1720-1735.
[[code]](https://github.com/ningpang/SCL_ZSRE) 
  
- `Ning Pang`, Wansen Wu, Yue Hu, Kai Xu, Quanjun Yin, Long Qin. Enhancing Multimodal Sentiment Analysis via Learning from Large Language Model. IEEE **ICME**, 2024. [[code]](https://github.com/ningpang/ArkMSA) 
  
- `Ning Pang`, Xiang Zhao, Weixin Zeng, Ji Wang, Weidong Xiao. Personalized Federated Relation Classification over Heterogeneous Texts. ACM **SIGIR**, 2023. 
[[code]](https://github.com/ningpang/pf-RC) 
  
- Zenghua Liao, Zongqiang Yang, Peixin Huang, `Ning Pang`, Xiang Zhao. Multimodal Fusion-based Hierachical Extraction for Chinese Epidemic Event. Data Science and Engineering (**DSE**). 2023, 8: 73-83.

- `Ning Pang`, Xiang Zhao, Wei Wang, Weidong Xiao, Deke Guo. Few-shot Text Classification by Leveraging Bi-directional Attention and Cross-class Knowledge. Science China Information Sciences (**SCIS**). 2021, 64, 130103. [[code]](https://github.com/ningpang/BACK) 
  
- `Ning Pang`, Xiang Zhao, Weidong Xiao. Chinese Text Classification via Bidirectional Lattice LSTM. **KSEM**, 2020. <font color="red">[Best Student Papr]</font> 
[[code]](https://github.com/ningpang/Ch-TC) 
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

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
