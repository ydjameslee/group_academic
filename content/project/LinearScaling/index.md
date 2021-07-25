---
title: Developing linear-scaling quantum mechanical methods
summary: 
tags:
- linearscaling
date: "2016-04-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: 
  focal_point: Smart

links:
# - icon: link
#   icon_pack: fas
#   name: link
#   url: https://www.nature.com/articles/s41565-020-00791-2.pdf?origin=ppub
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---
A linear-scaling time-dependent density-functional theory is developed to evaluate the optical response of large molecular systems. The two-electron Coulomb integrals are evaluated with the fast multipole method, and the calculation of exchange-correlation quadratures utilizes the locality of exchange-correlation functional within the adiabatic local density approximation and the integral prescreening technique. Instead of many-body wave function, the equation of motion is solved for the reduced single-electron density matrix in the time domain. Based on its ‘‘nearsightedness’’, the reduced density matrix cutoffs are employed to ensure that the computational time scales linearly with the system size. As an illustration, the resulting time-dependent density-functional theory is used to calculate the absorption spectra of linear alkanes, and the linear scaling of computational time versus the system size is clearly demonstrated.


A time-dependent density-functional tight-binding method in real time domain is developed to calculate the absorption spectra of very large systems. The time-dependent first-order response of the density matrix due to an external perturbation is solved using Chebyshev method with high efficiency and accuracy. Linear scaling of CPU time and memory usage with the system size is achieved by exploring the sparsity of the involving matrices as well as by introduction of a cutoff for the first-order density matrix. The compressed sparse row scheme is used to store the matrices, and SPARSEKIT is employed for sparse matrix multiplication. The absorption spectra of three-dimensional water clusters (H2O)216, (H2O)432, (H2O)648 and (H2O)864 are calculated using the present approach. The error due to the cutoff of density matrix is negligible. It is shown from these calculations that the presented method is very efficient and capable of calculating the absorption spectra for very large three-dimensional systems.
