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
keywords: conservation measures, forest health, business
abstract: |
  Tools used in the planning of conservation projects, such as Miradi and the Open Standards for the Practice of Conservation, help practitioners to carry out their work in a systematic manner, but they provide very little assistance with the geospatial analysis and mapping that are essential to conservation strategies. Furthermore, the methodologies employed in conservation action planning do not include an empirical evaluation of ecological conditions at the landscape level, which means that practitioners are forced to carry out geospatial analysis as a separate and independent activity. Drawing on examples from the Marin County Forest Health Strategy—such as fire history, the spread of young Douglas-fir beyond the recent fire perimeters, and the areas that have been mapped as departing from desired conditions—we look at cases in which geospatial analysis is directly integrated with these conservation planning frameworks. We demonstrate how situation models, theories of change, and results chains can connect the variables that drive ecosystems with business operations to conservation objectives, treatments, and measurable outcomes. We then describe a learning-and-adaptation feedback loop and give readers access to the Forest Business Alliance templates and guidance for implementing such integrated practices over large landscapes.
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

**CHANGE TITLE TO CMP GEOSPATIAL CASE STUDY** OR SOMETHING LIKE THAT AND REMOVE THE BUSINESS PLANNING ANGLE


:::{figure} images/geo.png
:alt: geo.png
:::

> "A starting quote" 

:::{important} Important dropdown
:class: dropdown

Here is the text for an important dropdown
:::

# Overview
Conservation project planning, implementation, and measurement is no easy task. The  Open Standards for the Practice of Conservation  are an incredible resource for practitioners to organize their approach in a systematic way that can increase their chances of success at the site scale. Miradi software is a fantastic way to manage the process and connect the different planning steps.

However, both Miradi and the Standards fall short for geospatial analysis and mapping, critical components of any conservation project for understanding natural conditions, their changes, and where to focus and prioritize interventions to reduce threats and improve species and habitat conditions. Furthermore, conservation action planning methodologies lack empirical assessment of ecological conditions at the landscape scale (@low). To compensate, practitioners conduct geospatial analysis separately.

In this article, we examine several cases that integrate the standards with geospatial analysis and consider how further integration could help scale practices across broad landscapes.

# Forests
Let's consider the Marin Forest Health Strategy. Focused on Marin County public lands, the strategy examined how to protect forest health amid climate change, increasing fire risk, disease, and other threats. Fire is a major driver of vegetation diversity in this Mediterranean ecosystem. Fire incidence since 1878 (red polygons) is frequent in some areas, but others have not burned for more than 140 years ({numref}`fire-marin`).

:::{figure} images/fire.png
:label: fire-marin
:height: 400px
Fire history in the Marin landscape (Source: FRAP).
:::

If we zoom in further and add young stands of Douglas-fir, *Pseudotsuga menziesii*(classified as trees < 18 m or 60', yellow), we see many fir stands outside of fire perimeters ({numref}`doug-marin`). Without fire, Douglas-fir acts as an invasive species. The yellow stands indicate where invasions may be occurring and help managers prioritize where to apply fire or remove young Douglas-fir at the landscape scale.

:::{figure} images/doug.png
:label: doug-marin
:height: 400px
Distribution of young Douglas-fir stands (yellow), with fire history perimeters shown in red in western Marin County (@marin).
:::

# Models
Let's step back and discuss the overall Douglas-fir situation model in Marin County. The situation model is a box-and-arrow diagram showing the causal relationships among factors that affect conservation targets (@cmp).

In the Marin Douglas-fir model, healthy Douglas-fir stands (green) contribute many ecosystem services (light blue) but are threatened by factors such as severe fire, climate change, pathogens, and unmanaged recreation, among others (red and orange) ({numref}`doug-sm`).

:::{figure} images/sm.png
:label: doug-sm
:height: 500px
Situation model of Douglas-fir in Marin County. Ecosystem services (blue), conservation scope (green), forest health attributes (purple), threats (red), indirect threats or contributing factors (orange), interventions (yellow), connections (white arrows), climate connections (red arrows)
:::

Local scientists and practitioners developed these factors in a situation model. The model shows relationships among multiple factors and provides a basis for developing treatments or interventions (yellow boxes) to reduce threats to healthy Douglas-fir stands.

For example, beneficial fire kills young Douglas-fir, reduces understory competition, and helps mature trees flourish and increase resilience to disturbance ({numref}`rc1-doug`).

**REDO OR FIND THE ORIGINAL RESULTS CHAIN AND EDIT EXPLANATION**

:::{figure} images/rc2.png
:label: rc2-doug
:height: 200px
Results chain zoom 2
:::

This yields interim results of reduced fire risk, long-term outcomes of fire-resilient stands, and increased biodiversity ({numref}`rc2-doug`).

The Douglas-fir classification provides a quick look at departures from desired conditions for some systems, but we developed a more detailed map using multiple variables. Let's take a look. Zooming in, you can see the detail from most departed from desired conditions (dark blue) to least departed (light blue). In this area, the greatest departure from desired conditions is generally due to sudden oak death syndrome (Phytophthora ramorum), fire exclusion, and early seral Douglas-fir impacts ({numref}`dep-bolinas`).

:::{figure} images/departure.png
:label: dep-bolinas
:height: 200px
Departure from desired conditions (@marin).
:::

# Planning
So what does this have to do with business planning? A primary link is putting your business in the context of a whole program or portfolio by developing a situation model or theory of change. Second, any forest-based business must consider ecosystem system driver variables, their effects on the resource, and the business's impact on those variables.

Let's look at a theoretical example. Any business plan should start with a situation model or theory of change. This causal box-and-arrow diagram shows the relationships in the system you're working on and why your solution or intervention will help solve a critical problem. In the simplified model showing the threat of an altered fire regime to the targeted forest stands, the threats in red (altered fire regime, lack of age-class diversity) are driven by contributing factors (in orange) such as historic fire suppression, climate change, and lack of seedling recruitment. The model also shows the assumptions underlying the identified causal relationships.

# Learning
The intended strategy or treatment is thinning with beneficial fire. A results chain linking the treatments to interim results (blue) and outcomes (purple) sets the stage for implementation and for measuring results during implementation ({numref}`steps-for`). Indicators (purple triangles) show monitoring along the way and link to objectives or goals in Step 3 (light blue ovals). A feedback loop of learning and adaptation runs from Step 3 to Step 1 as analysis is undertaken, and the business or group reflects on the results, possibly presenting them to a wider audience. During this learning, further adjustments to the situation model or theory of change can occur.

:::{figure} images/steps.png
:label: steps-for
:height: 500px
Generic forest treatment planning steps.
:::

For Forest Business Planning, see the [Forest Business Alliance templates page](https://forestbusinessalliance.org/templates.html) and the [FBA Guide](https://3point.xyz/fba-guide/), including Chapter 2: Program Design and Chapter 11: Startup Pathways.