---
# === Required fields  ===
# Your name 
name: "Hi, I'm Marcus Merryfield (he/him)! 👋🏻"
# Your profile picture
imgname: 
  name: "/static/img/me.jpg"
  alt: "Profile picture"
  type: image/jpeg
# More sources can be added (optional) using 
# imgOther:
#   - name: $IMAGE_PATH
#     type: $IMAGE_TYPE
#   - name: $IMAGE_PATH
#     type: $IMAGE_TYPE
# ...
# A title (job title or "Researcher", "PhD student", etc.)
personal_title: "👨🏻‍🎓 PhD Student at McGill"
# An address (you can list multiple)
address: 
  - 
    name: Trottier Space Institute
    street:  3550 Rue University
    locality: Montreal, QC
    email: marcus.merryfield@mail.mcgill.ca

# === Optional fields ===
# Add an email with a mailto: hyperlink
# email: marcus.merryfield@mail.mcgill.ca
# Add an email "image" for spam protection. With light and dark mode
# emailImg: 
#   dark: /img/dark_email.png
#   light: /img/light_email.png

# List your publications. The required fields are pdf, title, and image 
# (which should be the image path). The other fields are optional.
publications:
  - 
    authors:
        - name: Merryfield, M. 
          me: true
        - name: Tendulkar, S. P. 
        - name: Shin, K.
        - name: et al.
    title: "An Injection System for the CHIME/FRB Experiment"
    # Will write "In ${journal}, ${date}"
    date: 2023
    journal: The Astrophysical Journal
    image: img/inj_sys_paper.png
    # A bibtex (or any other format) citation that people can copy directly from the website.
    citation: "@ARTICLE{2023AJ....165..152M,\n
       author = {{Merryfield}, Marcus and {Tendulkar}, Shriharsh P. and {Shin}, Kaitlyn and {Andersen}, Bridget and {Josephy}, Alexander and {Good}, Deborah and {Dong}, Fengqiu Adam and {Masui}, Kiyoshi W. and {Lang}, Dustin and {M{\"u}nchmeyer}, Moritz and {Brar}, Charanjot and {Cassanelli}, Tomas and {Dobbs}, Matt and {Fonseca}, Emmanuel and {Kaspi}, Victoria M. and {Mena-Parra}, Juan and {Pleunis}, Ziggy and {Rafiei-Ravandi}, Masoud and {Sand}, Ketan R. and {Scholz}, Paul and {Smith}, Kendrick and {Stairs}, Ingrid H.},\n
        title = {An Injection System for the CHIME/FRB Experiment},\n
      journal = {\aj},\n
     keywords = {Radio transient sources, Radio interferometers, 2008, 1345, Astrophysics - Instrumentation and Methods for Astrophysics},\n
         year = 2023,\n
        month = apr,\n
       volume = {165},\n
       number = {4},\n
          eid = {152},\n
        pages = {152},\n
          doi = {10.3847/1538-3881/ac9ab5},\n
archivePrefix = {arXiv},\n
       eprint = {2206.14079},\n
 primaryClass = {astro-ph.IM},\n
       adsurl = {https://ui.adsabs.harvard.edu/abs/2023AJ....165..152M},\n
      adsnote = {Provided by the SAO/NASA Astrophysics Data System}\n
}

"
    pdf: https://ui.adsabs.harvard.edu/abs/2023AJ....165..152M/abstract
    # A description for the paper.
    description: Dedicated surveys searching for fast radio bursts (FRBs) are subject to selection effects that bias the observed population of events. Software injection systems are one method of correcting for these biases by injecting a mock population of synthetic FRBs directly into the real-time search pipeline. This paper presents an injection system developed for the Canadian Hydrogen Intensity Mapping Experiment Fast Radio Burst Project (CHIME/FRB).
---

# 🦠 Bio

I am a third year PhD student in the department of Physics at McGill studying fast radio bursts with Professor Vicky Kaspi in the CHIME Fast Radio Burst group. I helped build the [injection system](https://ui.adsabs.harvard.edu/abs/2023AJ....165..152M/abstract) for the project, which injects synthetic pulse data into the live telescope datastream as a way to help understand the search pipeline's selection biases.