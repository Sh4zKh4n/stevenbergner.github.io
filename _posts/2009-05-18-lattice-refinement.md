---
layout: post
title:  "Lattice refinement for experimental design"
date:   2009-05-18
breadcrumb: index
categories: research
collab:
- <a href="http://miplab.epfl.ch/index.php/people/vandeville">Dimitri Van De Ville</a>
- <a href="http://www.ee.cuhk.edu.hk/~tblu">Thierry Blu</a>
- <a href="https://cs.univie.ac.at/vda/team/worker/infpers/Torsten_M%C3%B6ller">Torsten M&ouml;ller</a>
---
In this project we are looking at constructing sub-sampling schemes for lattices that allow for a fixed reduction factor in the number of samples that is independent of the dimensionality of the lattice.

Our results were presented at <a href="http://www.latp.univ-mrs.fr/SAMPTA09/">SAMPTA 2009</a> with an extended discussion in Chapter 3 of my [PhD thesis][phdlibrary] ([PDF][phdpdf]).

![Three different solutions for 2-scale refinement in 2D][rotgrid2d-img]

Each column shows a different lattice with several levels of refinement.
The *top row* shows the refined lattice as small grey dots and the coarse sub-lattice is shown as thick dots.
The Voronoi cells, or so-called nearest neighbour cells, for the two nested lattices are also shown.
The *bottom row* shows the same lattices as in the top with additional levels of refinement.

The special property of the nested lattice sequences we construct is that each lattice is a scaled and rotated version of the other lattices in the sequence. We show how to obtain such lattices for low distance scaling factors, such as $2^{1/d}$ that change the density by a factor of 2.

[rotgrid2d-img]: {{ site.baseurl }}/assets/img/rotgrid-levels-d2-beta2.png "Three different solutions for 2-scale refinement in 2D"
[phdpdf]: http://summit.sfu.ca/system/files/iritems1/12089/etd7005_SBergner.pdf "PhD thesis PDF file"
[phdlibrary]: http://summit.sfu.ca/item/12089 "Making choices in multi-dimensional parameter spaces"