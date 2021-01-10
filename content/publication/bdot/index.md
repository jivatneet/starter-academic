---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Simulation and Selection of Detumbling Algorithms for a 3U CubeSat (IAC 2019)"
authors: ["Vishnu P Katkoori", admin, "Tushar Goyal"]
date: 2019-10-21T22:43:22+05:30
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-12-06T22:43:22+05:30

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "*Proceedings of the 70th International Astronautical Congress (IAC)*"
publication_short: "IAC 2019"

abstract: "As a satellite is deployed from the launch vehicle, it is subjected to high angular rates which need
to be dampened in order for the satellite to perform its functions as expected. Simple and robust algorithms, such as BDot, are generally used to provide the required control torque for detumbling the
satellite. This paper elucidates the design process for the detumbling algorithm to be implemented on
a nanosatellite currently being developed by Team Anant, the Student Satellite Team of BITS Pilani.
The process commenced with the selection of hardware to be used onboard the satellite. Magnetometers
and Gyroscopes were finalized to be used as sensors. Various commercially available sensor models were
then compared based on power and operating conditions. For actuation, a magnetorquer system was
designed specifically to the requirements of the team. The system comprised of two magnetorquer rods
and a magnetorquer coil aligned in orthogonal directions. The sensors and actuators were then accurately
modeled in MATLAB for further testing. The modeling involved some interesting challenges due to the
magnetic moment retained by the ferromagnetic core. These challenges, and the ways to overcome them
have been also been briefly discussed in the paper. After finalizing the hardware, the team proceeded
with implementing various popular control algorithms for detumbling the satellite. The algorithms were
first theoretically analysed, and then modeled on MATLAB. The simulations took the space environment
around the satellite into consideration for higher accuracy. The algorithms were tested for different initial
conditions, using different time-steps and under different power constraints. The algorithms considered
and the conclusions derived from these simulations have also been discussed elaborately in this paper.
The paper concluded by presenting the finalized detumbling algorithm(s) to be used by Team Anant,
and the various conditions devised to ensure efficient use of electrical power. The paper also presents
viable alternatives to the finalized algorithm(s), using other hardware components. These alternatives
and conditions have also been documented in the paper for a better understanding."

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

url_pdf: "https://team-anant.org/papers/IAC-19,B4,9-GTS.5,10,x53342.pdf"
url_code: 
url_dataset: 
url_poster:
url_project:
url_slides:
url_source: 
url_video:

links:
  - url: 'https://iafastro.directory/iac/paper/id/53342/summary/'
    # icon_pack: fab
    # icon: twitter
    name: Abstract


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
