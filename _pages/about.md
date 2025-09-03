---
permalink: /
title: "Academic Pages is a ready-to-fork GitHub Pages template for academic personal websites"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Welcome to my website. This is a project I started in August 2025 with the goal of building a central place to document and share my research portfolio. It includes past and present projects, ideas for the future, and even a section for stories and personal bits [here](https://jdavidpoling.github.io//year-archive/).

Who Am I?
======
I am an American Marine Scientist currently based in Southern Norway, where I am doing my PhD with the University of Agder in [Coastal Ecology](https://www.uia.no/english/research/phd-programmes/index.html) and have an office at the IMR [Flødevigen Research Station](https://www.hi.no/en/hi/laboratories/flodevigen-research-station). My masters' is in Coastal Environmental Management from Duke University where I worked with Dave Johnston and the Marine Robotics and Remote Sensing [(MaRRS) Lab](https://marineuas.net/new/). My bachelors is in Marine Science with a minor in Applied Ecology from North Carolina State University where I did my bachelors thesis with Ryan Paerl's [Microbial Ecology Lab](https://paerllab.wordpress.ncsu.edu/). 

PhD Work
======
My PhD work focuses on the development of machine learning methods for studying marine fauna. This includes development of new models and ML-based workflows to analyze remote underwater video (BRUV/RUV) as well as working with fish indivudal re-identification for coastal cod. I am also leading a visual survey of Raet National Park here in Southern Norway looking at the effects of bottom trawling. 

Computer Vision in Marine Ecology
======
One of the main focuses of my work since my masters has been the development and implementation of computer vision/machine learning based methods for marine ecology. This has involved behavior tracking, faunal classification and now even individual re-identification in fish.

**Detection and Classification**
---
The most basic of these tasks are detection and classification. Detection involves having the model tell us when something appears in our imagery, either still images or from a video stream. Without classification, detection would just label every target it sees as "fish" in underwater imagery, or "vehicle" in traffic camera footage. Classification takes us one step further and has the model predict what category an object may belong to. For surveying fish populations in southern Norway, this is differentiating between cod and pollack, or classifying wrasses based on sex using their sexual dimorphism.

**Individual Re-Identification**
---
Individual re-identification (ReID) is a type of classification task where the model has to assign detections not only to a species or species group, but to a specific individual animal. This is like identifying whales based on their fluke patters, or your dog at the dog park based on its coat and patterns. We are interested in ReID for fish as it allows us to track invidual fish over time using cameras, without having to every catch and tag them. An "open-set" ReID system would also be able to add new individuals automatically and re-id them if they appeared again later.

To implement Re-ID for fish, we are starting with coastal cod (Gadus morhua). This species is not only ecologically important but also 

Some existing work on animal re-identification my collaborators and others:
- A contrastive learning approach for individual re-identification in a wild fish population (corkwing wrasse) [Link](https://arxiv.org/abs/2301.00596)
- WildlifeDatasets: An Open-Source Toolkit for Animal Re-Identification (not species specific) [Link](https://openaccess.thecvf.com/content/WACV2024/html/Cermak_WildlifeDatasets_An_Open-Source_Toolkit_for_Animal_Re-Identification_WACV_2024_paper.html)
- WildlifeReID-10k: Wildlife re-identification dataset with 10k individual animals [Link](https://arxiv.org/abs/2406.09211)

**Remote Underwater Video**
---
We used underwater cameras to study many different aspects of the marine realem, from population counts, habitat condition, behavioral studies and more. The most common setup we use is a Baited Remote Underwater Video rig (BRUV). BRUVs use stereo-video (two cameras looking forwards) to give us depth perception for distance and length measurements. BRUVs are also baited (a BRUV with no bait is a RUV) which attracts individuals to the cameras to increase survey efficiency. Using bait is not appropriate for all studies, but as long as it is used in a documented systematic manner, it allows for the generation of large volumes of good data.

Want to Chat?
------
If you have a specific question or would like to chat anything marine science or remote sensing, you can reach me at any of the links on the left hand of this page (below my face). My university email is where you will likely get the quickets response. If your question directly relates to any of my projects on GitHub you can also leave a note in "Issues" or "Discussions" in those repositories.
