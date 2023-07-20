# Multi-echo fMRI: OHBM 2023

This contains materials related to tedana and multi-echo fMRI presented at the Organization for Human Brain Mapping 2023 Annual Meeting

 This is a place to centralize multi-echo related content at OHBM 2023. If you see or have a poster or presentation using multi-echo fMRI, submit a pull request or [comment on issue #1](https://github.com/ME-ICA/ohbm-2023-multiecho/issues/1) to have it added.

## Multi-echo presentations

### Characterizing the Effects of Multiecho and Multiband Imaging on Corticostriatal Responses to Reward

David Smith, Jeffrey Dennison, Ori Zaff, James Wyngaarden, Makayla Collins, Logan Dowdle, Johanna Jarcho, Ingrid Olson, Ben Inglis, Paul Morgan, Chris Rorden, Dominic Fareri 

**Talk** Wed, 7/26, 10:30 AM - 11:45 AM, Palais, Room 513

Poster TuWed 1958

[Abstract](https://ww6.aievolution.com/hbm2301/index.cfm?do=abs.viewAbs&abs=2966)

### Open Science Room Emergent Session: Physiopy open meeting: physiology community practices + Challenges for small collaborative software projects

**Panel Discussion** Tues, 7/25, 14:25 - 16:15

In Open Science Room or [Join on Crowdcast](https://www.crowdcast.io/e/osr-2023-emergent-5)

By the Physiopy community, the tedana community, and the neurokit project, hosted by Stefano Moia, Ecole Polytechnique Federale de Lausanne, and Daniel Handwerker, Section on Functional Imaging Methods, NIMH.

With the spread of open science practices, new ways of collaborating on scientific projects are taking root. One of these are international, cross-lab communities that gather around community practices, documentation, and software development.
While there are great examples of large, stable international collaborations, consortia, and community-developed projects (e.g. BIDS, nipreps, The Touring Way, ...), methods development often happens in smaller projects united by a specialized need.

This emergent session is dedicated to these smaller realities.
In the first part (first 45 minutes), you are invited to partake in an open community meeting centered on Physiopy and engage in a discussion of community practices, specifically about physiological topics. In the second part (second 45 minutes), we will reflect across communities on what are the challenges these types of collaborations face, our challenges and successes, and how we can deal with them.

## Multi-echo posters

### Tedana: A Growing Multi-Echo fMRI Ecosystem

**Tedana Community**: Peter A. Bandettini, Logan Dowdle, Elizabeth DuPre, Javier Gonzalez-Castillo, Daniel Handwerker, Angela Laird, Kasamba Lumwagi, Stefano Moia, Neha Reddy, Taylor Salo, Joshua Teves, Eneko Uruñuela

Poster SuMon 130

[Abstract](https://ww6.aievolution.com/hbm2301/index.cfm?do=abs.viewAbs&abs=2339)

[Poster](./tedana/tedana_poster_OHBM2023.pdf)

<!--- [Poster]() | [Poster pdf](./tedana_poster_OHBM2023.pdf) --->

**Sample interactive reports from tedana**: All reports use a block design flashing checkerboard task with 5 echoes.
The reports were generated using [process_5echo_blockdesign.ipynb](process_5echo_blockdesign.ipynb)

- [Results using the kundu decision tree](https://me-ica.github.io/ohbm-2023-multiecho/tedana/tedana_results_kundu_five-echo/tedana_report.html)
- [Results using the minimal decision tree](https://me-ica.github.io/ohbm-2023-multiecho/tedana/tedana_results_minimal_five-echo/tedana_report.html)
- [Results using ica_reclassify to change a component classification after the kundu decision tree](https://me-ica.github.io/ohbm-2023-multiecho/tedana/ica_reclassify_five-echo/tedana_report.html)

### Multi-echo ICA for motor-task fMRI group analysis with amplified task-correlated head motion

 Neha Reddy, Kristina Zvolanek, Stefano Moia, César Caballero-Gaudes, Molly Bright

Poster SuMon 115

[Abstract](https://ww6.aievolution.com/hbm2301/index.cfm?do=abs.viewAbs&abs=1025)

### Multi-echo ICA denoising increases tSNR in combined cortical and brainstem task-fMRI

 Neha Reddy, Rebecca Clements, Molly Bright

Poster SuMon 732

[Abstract](https://ww6.aievolution.com/hbm2301/index.cfm?do=abs.viewAbs&abs=2873)

### Adapting T2* based combination for fetal multi-echo fMRI

Amyn Majbri, Lanxin Ji, Ellyn Kennelly, Cassandra Hendrix, Tanya Bhatia, Mark Duffy, Moriah Thomason

Poster SuMon 775

[Abstract](https://ww6.aievolution.com/hbm2301/index.cfm?do=abs.viewAbs&abs=4187)

### Extending fMRIPrep to MEPrep: an improved preprocessing pipeline for multi-echo functional MRI

Zhishun Wang, Feng Liu, Gaurav Patel, Rachel Marsh, Jack Grinband

Poster SuMon 795

[Abstract](https://ww6.aievolution.com/hbm2301/index.cfm?do=abs.viewAbs&abs=4122)

### Multi-echo fMRI removes physiological noise during naturalistic viewing

Micah Holness, Joshua B. Teves, Tyler Morgan, Gang Chen, Javier Gonzalez-Castillo, Peter A. Bandettini, Daniel A. Handwerker

Poster SuMon 911

[Abstract](https://ww6.aievolution.com/hbm2301/index.cfm?do=abs.viewAbs&abs=2426) | [Github repo](https://github.com/nimh-sfim/ComplexMultiEcho1)

### Increased insular activity during interoceptive attention

Matthias Müller-Schrader, Frederike Petzschner, Jakob Heinzle, Lars Kasper, Katharina Wellstein, Johanna Bayer, Maria Engel, Klaas P Pruessmann, Klaas E. Stephan

(Anatomical multi-echo)

Poster SuMon 160

[Abstract](https://ww6.aievolution.com/hbm2301/index.cfm?do=abs.viewAbs&abs=3926)

### Comparison of Myelin Water Imaging from Multi-echo T2 Decay and Myelin Content from Synthetic MRI

Jing Zhang, David Shin, Suchandrima Banerjee

(Anatomical multi-echo)

Poster SuMon 1054

[Abstract](https://ww6.aievolution.com/hbm2301/index.cfm?do=abs.viewAbs&abs=1063)

### Appraisal of multi-echo fMRI sequences for psychedelics studies

Leonardo Novelli, Adeel Razi

Poster SuMon 1153

[Abstract](https://ww6.aievolution.com/hbm2301/index.cfm?do=abs.viewAbs&abs=3049)

### A preliminary study on reliability of multi-echo EPI in resting state functional MRI on compact 3T

Daehun Kang, Kirk Welker, Myung-Ho In, Dora Hermes, John III Huston, Matt Bernstein, Yunhong Shu

Poster SuMon 1155

[Abstract](https://ww6.aievolution.com/hbm2301/index.cfm?do=abs.viewAbs&abs=3081)

### Age differences in basal forebrain functional connectivity and volume are related to attention

Miriam Taza, Taylor Schmitz, Roni Setton, Laetitia Mwilambwe-Tshilobo, Gary Turner, R. Nathan Spreng

Poster TuWed 2264

[Abstract](https://ww6.aievolution.com/hbm2301/index.cfm?do=abs.viewAbs&abs=2388)