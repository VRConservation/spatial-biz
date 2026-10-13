---
title: Spatial Business Planning
subject: Forests & Business
subtitle: Scaling forestry businesses with situation assessments and geospatial analysis 
short_title:
date: 2023-08-17
authors:
  - name: Vance Russell
    affiliations: 
      - 3point.xyz
    email: vance@3point.xyz
  - name: Chris Sacco
    affiliations: 
      - Aegis Conservation Ecology
    email: chris@aegisconservation.com    
keywords: 
abstract: |
  Add abstract here
kernelspec:
  name: python3
  display_name: Python 3
exports:
  - format: docx
    template: curvenote
    output: article-name.docx
    article_type: Report
  - format: typst
    template: lapreprint-typst
    output: article-name.pdf     
---

:::{figure} images/geo.png
:alt: geo.png
:::

> "A starting quote" 

:::{important} Important dropdown
:class: dropdown

Here is the text for an important dropdown
:::



# OVERVIEW
Conservation project planning, implementation, and measurement is no easy task. The  Open Standards for the Practice of Conservation  are an incredible resource for practitioners to organize how they approach this work in a systematic way that can increase their chances of success at the site scale. Miradi software is a fantastic way to manage the process and connect the different planning steps.

However, both Miradi and the Standards are insufficient for geospatial analysis and mapping, critical components of any conservation project to understand the natural conditions, changes to them, and where to focus and prioritize interventions to reduce threats and improve species and habitat conditions. Furthermore, conservation action planning methodologies lack empirical assessment of ecological conditions at the landscape scale (@low). To compensate, practitioners conduct geospatial analysis separately.

In this storymap we examine several cases that integrate the standards with geospatial analysis and consider how further integration could be useful for scaling practices across broad landscapes.

# FORESTS
Let's consider the Marin Forest Health Strategy. Focused on Marin County public lands, the strategy examined how to protect forest health in the face of climate change, increasing fire risk, disease, and other risks. Fire is a major driver of vegetation diversity in this Mediterranean ecosystem. Fire incidence since 1878 (red polygons) are frequent in some areas, but others have not burned for more than 140 years ({numref}`fire-marin`).

:::{figure} images/fire.png
:label: fire-marin
:height: 400px
Fire history of in the Marin landsacpe (Source: FRAP).
:::

If we zoom in further and add young stands of Douglas-fir (classified as trees < 18 m or 60', yellow), we see many fir stands outside of fire perimeters. Without fire, Douglas-fir acts as an invasive species. The yellow stands give managers an indication of where invasions may be occurring and prioritize where to apply fire or remove young Douglas-fir at the landscape scale.