---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Modeling the Data-Generating Process is Necessary for Out-of-Distribution Generalization"
authors: [admin, "Emre Kiciman", "Amit Sharma"]
date: 2023-01-21T22:43:22+05:30
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2022-01-21T22:43:22+05:30

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "*Eleventh International Conference on Learning Representations*"
publication_short: "*ICLR 2023 (Spotlight)*"

abstract: "Recent empirical studies on domain generalization (DG) have shown that DG algorithms that perform
well on some distribution shifts fail on others, and no state-of-the-art DG algorithm performs
consistently well on all shifts. Moreover, real-world data often has multiple distribution shifts over
different attributes; hence we introduce multi-attribute distribution shift datasets and find that the
accuracy of existing DG algorithms falls even further. To explain these results, we provide a formal
characterization of generalization under multi-attribute shifts using a canonical causal graph. Based
on the relationship between spurious attributes and the classification label, we obtain realizations of
the canonical causal graph that characterize common distribution shifts and show that each shift entails
different independence constraints over observed variables. As a result, we prove that any algorithm
based on a single, fixed constraint cannot work well across all shifts, providing theoretical evidence
for mixed empirical results on DG algorithms. Based on this insight, we develop *Causally Adaptive
Constraint Minimization (CACM)*, an algorithm that uses knowledge about the data-generating process
to adaptively identify and apply the correct independence constraints for regularization. Results on
fully synthetic, MNIST, small NORB, and Waterbirds datasets, covering binary and multi-valued
attributes and labels, show that adaptive dataset-dependent constraints lead to the highest accuracy on
unseen domains whereas incorrect constraints fail to do so. Our results demonstrate the importance
of modeling the causal relationships inherent in the data-generating process."

# Summary. An optional shortened abstract.
summary: ""

tags: []
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: 'https://arxiv.org/pdf/2206.07837.pdf'
url_code: 
url_poster: 
url_dataset: 
url_project:
url_slides: 
url_source: 
url_video:

links:
  - url: 'https://arxiv.org/abs/2206.07837'
    # icon_pack: fab
    # icon: twitter
    name: arXiv
  - url: 'https://slideslive.com/38988002/spotlights?time=1812'
    # icon_pack: fab
    # icon: twitter
    name: Talk
  - url: 'Poster_Latest.pdf'
    # icon_pack: fab
    # icon: twitter
    name: Poster



# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
