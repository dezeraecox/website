---
# [str] Title of the project. This is also visible when hovering over a gallery item.
title: "Dr Emma Harding"
# [str] Optional subtitle of the project. 
#   Functions as an additional explanation when hovering over a gallery item (comment out the following line).
subtitle: " "
# [date] Project publication date.
#   Changes order: The newest item will be displayed first in the gallery. 
#   Just like Hugo's natural ordering, this is anti-chronological.
#   You can use 'weight' to order (primarily) for more control (sometimes it makes sense to put old items before new ones).
weight: 3

#   The specifics are documented here: https://gohugo.io/templates/lists/#order-content
date: "2024-03-24T20:36:42+11:00"
# [str] Gallery image file from the assets directory. 
image: "/images/bios/EH.png"
# [str] Alternative (image) description.
alt: ""
# [css] Optional background color of the gallery item (if omitted, will use theme's fallback).
color: "#131c31"
# color: "#373F51"
# [css] Optional gallery item hover color (if omitted, will use theme's fallback).
# hoverColor: "#fff"
# [map] Configure github specific options here:
# github: 
    # [str] Repo is a combination of "<user_or_org>/<repository_name>"
    # repo: "<username>/themes"
    # [bool] Show repository information such project language below the buttons.
    # showInfo: true
    # showButtons: true
# [map] Optionally configure terminal to be displayed when opening up the gallery item:
#   Example (set "useTermynal" to true in config.yaml and comment out to test it):
# terminal:
    # lines:
    # - type: input
    #   data: hugo mod get -u github.com/hugo-mods/lazyimg 
    #   wait: 1250
    # - type: progress
    #   data: 100
    #   wait: 200
    # - data: ✓ Done.
    #   wait: 75
    # - data: exit
    #   wait: 75
# buttons:
#   - i18n: view # i18n key (see i18n directory, see https://gohugo.io/functions/i18n/)
#     icon: view # optional: use an icon from icons.yaml
#     newTab: false # optional: controls if url should be opened in new tab
#     url: ""
#   - i18n: code 
#     icon: code
#     url: ""
# # [bool] Draft mode will decide if file will be published to 'public/' directory.
# draft: false
---
<!-- ## Abstract -->

*Department of Biology, University of Oxford*

Emma is a paleovirologist studying the evolution, transmission and co-option of viruses in vertebrates. She completed her undergraduate studies and PhD at the University of New South Wales in Sydney before moving to the UK to work as a postdoctoral researcher at the University of Oxford. Traditionally trained as a molecular virologist, she has a background in wet-lab techniques, working to develop broad-spectrum antiviral candidates, monitor circulating viruses from clinical and environmental samples, and contribute to the NSW Health COVID-19 response through wastewater analysis of SARS-CoV-2. During her PhD, Emma transitioned to bioinformatic research and now exclusively works with computers, developing methods and analyses to understand overarching trends and patterns of virus evolution.

## Abstract

### Endogenous retroviruses as viral fossils: detection methods and evolutionary insights

Emma F Harding¹, Laura Munoz-Baena¹, Aris Katzourakis¹,

*¹Department of Biology, University of Oxford*

Retroviridae is an important viral family that contains many mammalian pathogens and has a long history of co-evolution with vertebrates. The obligate integration of retroviruses into host DNA during infection leads to endogenous retroviruses (ERVs), which can be passed on to progeny if integrated in a germline cell. These elements act as molecular “fossils”, providing insights into evolutionary trends over millions of years.
ERV classification is a difficult endeavour, with modern retroviruses representing only a fraction of their historical diversity. In addition, modern retroviruses are often the product of multiple historical recombination and transmission events, making tracing their evolutionary path challenging. We created a pipeline to detect ERVs based on sequence similarity to retroviral proteins using DIAMOND, reconstruct the ancestral proteins using Genewise and classify them with custom developed HMMs. We then systematically search and evaluate degradation of LTRs to date ERVs. Finally, we use MMseqs to cluster the reconstructed sequences, calculate k-mer distances and construct networks to visualise their relationships and connections.
Collecting data from 4,155 vertebrate genomes, we identify discrepancies in the types and rate of retroviral integration in different host orders, indicating the differential burdens that retroviral infections have on species over time. We also identify ERVs from recently circulating retroviruses to understand the transmission dynamics influencing the modern global retrovirome. Finally, we explore the origins of retroviral genera, expanding our understanding of the evolutionary patterns that shape this viral family. 
