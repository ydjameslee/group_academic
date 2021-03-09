---
# Display name
title: Jun LI

# Username (this should match the folder name)
authors:
- junli

# Is this the primary user of the site?
superuser: false

# Role/position
role: PostDoc

# Organizations/Affiliations
organizations:
- name: Beijing Computational Science Research Center
  url: "http://www.csrc.ac.cn/"
- name: Shenzhen JL Computational Science And Applied Research Institute
  url: ""
  

# Short bio (displayed in user profile at end of posts)
#bio: My research interests include distributed robotics, mobile computing and programmable matter.

#interests:
#- Artificial Intelligence
#- Computational Linguistics
#- Information Retrieval

education:
  courses:
    - course: PhD in Computational Chemistry
      institution: The University of Hong Kong
      year: 2018
    - course: MPhil in Physics
      institution: The University of Hong Kong
      year: 2010
    - course: BSc in Physics
      institution: Fudan University
      year: 2006

# Social/Academic Networking
# For available icons, see: https://sourcethemes.com/academic/docs/page-builder/#icons
#   For an email link, use "fas" icon pack, "envelope" icon, and a link in the
#   form "mailto:your-email@example.com" or "#contact" for contact widget.
social:
- icon: envelope
  icon_pack: fas
  link: 'mailto:lijun@csar.ac.cn'  # For a direct email link, use "mailto:test@example.org".
#- icon: twitter
#  icon_pack: fab
#  link: https://twitter.com/GeorgeCushen
#- icon: google-scholar
#  icon_pack: ai
#  link: 'https://scholar.google.com/citations?user=Z6cXcTEAAAAJ'
#- icon: github
#  icon_pack: fab
#  link: https://github.com/gcushen
# Link to a PDF of your resume/CV from the About widget.
# To enable, copy your resume/CV to `static/files/cv.pdf` and uncomment the lines below.
# - icon: cv
#   icon_pack: ai
#   link: files/cv.pdf

# Enter email to display Gravatar (if Gravatar enabled in Config)
email: "mailto:lijun@csar.ac.cn"

# Highlight the author in author lists? (true/false)
highlight_name: false

# Organizational groups that you belong to (for People widget)
#   Set this to `[]` or comment out if you are not using People widget.
user_groups:
- Researchers
---

Dr. Jun LI is a Postdoctoral Researcher at Shenzhen JL Computational Science And Applied Research Institute.
## Research 
My research focused on the fast algorithms in NEGF approach for steady-state quantum transport. The application of NEGF in quantum transport has led to tremendous success for the simulation of nano-device. However, the intensive computational cost in NEGF prohibits its application to realistic system at large scale, especially the device with multi-terminal setup. The major part of cost in self-consistent field (SCF) NEGF calculation comes from the evaluation of electron density, or Mulliken charge, which is obtained by numerical integration of Green’s function:the equilibrium part and non-equilibrium part. We exploits the sparsity of matrix to develop SelInv Algorithm and X-formulation Algorithm to speed up the Green’s function calculation. We also used the numerical integration technique: the multi-contour and adaptive quadrature to reduce cost and improve the accuracy of integration. The algorithms and techniques developed are applied to the realistic nano-device's simulation.
