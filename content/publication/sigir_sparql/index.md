---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Modern Baselines for SPARQL Semantic Parsing"
authors: ["Debayan Banerjee", co-author, "Pranav Ajit Nair*", "Ricardo Usbeck", "Chris Biemann"]
date: 2022-07-11T22:43:22+05:30
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2022-07-11T22:43:22+05:30

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "*The 45th International ACM SIGIR Conference on Research and Development in Information Retrieval*"
publication_short: "*SIGIR 2022*"

abstract: "In this work, we focus on the task of generating SPARQL queries from natural language questions, which can then be executed on Knowledge Graphs (KGs). We assume that gold entity and relations have been provided, and the remaining task is to arrange them in the right order along with SPARQL vocabulary, and input tokens to produce the correct SPARQL query. Pre-trained Language Models (PLMs) have not been explored in depth on this task so far, so we experiment with BART, T5 and PGNs (Pointer Generator Networks) with BERT embeddings, looking for new baselines in the PLM era for this task, on DBpedia and Wikidata KGs. We show that T5 requires special input tokenisation, but produces state of the art performance on LC-QuAD 1.0 and LC-QuAD 2.0 datasets, and outperforms task-specific models from previous works. Moreover, the methods enable semantic parsing for questions where a part of the input needs to be copied to the output query, thus enabling a new paradigm in KG semantic parsing."

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

url_pdf: 'https://arxiv.org/pdf/2204.12793.pdf'
url_code: 
url_dataset: 
url_poster:
url_project:
url_slides: 
url_source: 
url_video:

links:
  - url: 'https://arxiv.org/abs/2204.12793'
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
