---
title: "Ortholog cell-type deconvolution"
description: "Article to explain the logic and reasoning behind the method of ortholog-based cell-type deconvolution"
summary: ""
date: 2023-09-07T16:27:22+02:00
lastmod: 2023-09-07T16:27:22+02:00
draft: false
weight: 50
categories: []
tags: []
contributors: []
pinned: false
homepage: false
seo:
  title: "" # custom title (optional)
  description: "" # custom description (recommended)
  canonical: "" # custom canonical URL (optional)
  noindex: false # false (default) or true
---

 # Cell-type deconvolution

In technical terms, this is a tool to estimate the proportion of multiple cell types in a complex tissue.

An analogy for this problem, it is similar to analyzing forensic evidence in a crime scene such as fingerprints. Lets assume a robbery happens in a house. If we look at all the fingerprints identified in every surface of the house, the majority of evidence would belong to the people who lives in the house. However, a small fraction of those fingerprints will belong to the thief/thieves, friends, family or even some careless investigator that forgot to put gloves before poking around. Then, the nex wueation would be: how can we identify which fingerprints belong to who? We take each fingerprint found at the crime scene and we would compare them against a database that contains thousands of peoples' fingerprints. Using this matching method we will be able to assign an identity to each set of fingerprints.

Cell-type deconvolution uses a similar idea of first defining the "fingerprints" of each cell type and then tries to determine
