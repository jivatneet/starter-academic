---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Modeling the Data-Generating Process is Necessary for Out-of-Distribution Generalization"
authors: [admin, "Emre Kiciman", "Amit Sharma"]
date: 2022-07-17T22:43:22+05:30
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2022-07-17T22:43:22+05:30

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "*Workshop on Spurious Correlations, Invariance, and Stability at ICML 2022*"
publication_short: "*Workshop on Spurious Correlations, Invariance, and Stability at ICML 2022 (Spotlight)*"

abstract: "Real-world data collected from multiple domains can have multiple, distinct distribution shifts over multiple attributes. However, state-of-the art advances in domain generalization (DG) algorithms focus only on specific shifts over a single attribute. We introduce datasets with multi-attribute distribution shifts and find that existing DG algorithms fail to generalize. To explain this, we use causal graphs to characterize the different types of shifts based on the relationship between spurious attributes and the classification label. Each multi-attribute causal graph entails different constraints over observed variables, and therefore any algorithm based on a single, fixed independence constraint cannot work well across all shifts. We present Causally Adaptive Constraint Minimization (CACM), a new algorithm for identifying the correct independence constraints for regularization. Results on fully synthetic, MNIST and small NORB datasets, covering binary and multi-valued attributes and labels, confirm our theoretical claim: correct independence constraints lead to the highest accuracy on unseen domains whereas incorrect constraints fail to do so. Our results demonstrate the importance of modeling the causal relationships inherent in the data-generating process: in many cases, it is impossible to know the correct regularization constraints without this information."

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
url_dataset: 
url_poster:
url_project:
url_slides: 
url_source: 
url_video:

links:
  - url: 'https://arxiv.org/abs/2206.07837'
    # icon_pack: fab
    # icon: twitter
    name: arXiv
 # - url: 'https://akbc-cskb.github.io/videos/17.mp4'
    # icon_pack: fab
    # icon: twitter
    # name: Talk


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
