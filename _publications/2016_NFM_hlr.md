---
layout: publication
# The quotes make the : possible, otherwise you can do it without quotes
title: "Verifying Relative Safety, Accuracy, and Termination for Program Approximations"
key: 2016_NFM_hlr

#YYYY_CONFSHORTNAME_PAPERSHORTNAME
# paper | preprint | poster
type: paper
redirect_from: /publications/2016_NFM_hlr

# The shortname is used for auto-generated titels
shortname: 2016_OOPSLA_sdbgr
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/
image: 2016_NFM_hlr.png
# 2018_tvcg_lineage.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/
image_large: 2016_NFM_hlr.png
#2018_tvcg_lineage_teaser.png

# Authors in the "database" can be used with just the key (lastname). Others can be written properly.
authors:
- he
- Shuvendu K. Lahiri
- rakamaric

journal-short: NFM
year: 2016

#bibentry: article | inproceedings | phdthesis | book

bibentry: inproceedings
bib:
  journal:
  booktitle: Proceedings of the 8th NASA Formal Methods Symposium (NFM)
  editor: Sanjai Rayadurgam and Oksana Tkachuk
  publisher: Springer
  address: 
  doi:
  url: 
  volume: 9690
  number: 
  pages: 237--254
  month: 

# Add things like "Best Paper Award at InfoVis 2099, selected out of 4000 submissions"
award:

# Use if this paper is linked to an internal project. This will link to the project site
# project: upset

# Use this if you have an external project website
external-project:
#https://github.com/soarlab/FPTaylor

# The reference to the video entry
video:
# 2018_tvcg_lineage_video
# The reference to the preview viedo entry
#preview-video:

# the prerint
pdf: 2016_NFM_hlr.pdf
# A supplement PDF
supplement: 
#2018_tvcg_lineage_supplement.pdf

# Extra supplements, such as talk slides, data sets, etc.
supplements:
#- name: General UpSet
#  # use link instead of abslink if you want to link to the master directory
#  abslink: http://vials.io/talk/
#  # defaults to a download icon, use this if you want a link-out icon
#  linksym: true

# Link to the repository where the code is hostet
code: 

# Link to an official preprint server
preprint_server: 
#https://doi.org/10.1101/128579

abstract: "
Approximate computing is an emerging area for trading off the accuracy of an application for improved performance, lower energy costs, and tolerance to unreliable hardware. However, developers must ensure that the leveraged approximations do not introduce significant, intolerable divergence from the reference implementation, as specified by several established robustness criteria. In this work, we show the application of automated differential verification towards verifying relative safety, accuracy, and termination criteria for a class of program approximations. We use mutual summaries to express relative specifications for approximations, and SMT-based invariant inference to automate the verification of such specifications. We perform a detailed feasibility study showing promise of applying automated verification to the domain of approximate computing in a cost-effective manner.
"

# After the --- you can put information that you want to appear on the website using markdown formatting or HTML. A good example are acknowledgements, extra references, an erratum, etc.
---