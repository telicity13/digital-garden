+++
title = "Sentiment Analysis Research with the HathiTrust Digital Library"
description = "A digital humanities project exploring sentiment and language patterns in historical texts."
weight = 1
date = 2023-12-20

[extra]
github = ""
demo = "https://telicity13.github.io/digital-humanities/sentiment_analysis_research_hathitrust.html"
tags = ["digital humanities", "sentiment analysis"]
+++

## Overview

In this project, I conducted sentiment analysis using Python on two volumes from the HathiTrust Digital Library to examine how the emotional valence changes across each text. The book titles I analyzed were one fiction novel [*The Count of Monte Cristo*](https://hdl.handle.net/2027/mdp.39015062136661) by Alexandre Dumas and one nonfiction text [*The Origin of Species*](https://hdl.handle.net/2027/hvd.hw39sc) by Charles Darwin. My goal was to generate visualizations of the change in emotional valence over the span of these books.

I utilized two forms of textual data for my analysis: full text (TXT) files downloaded directly from HathiTrust Digital Library, as well as Extracted Features (EF) obtained from [HathiTrust Research Center (HTRC) Analytics](https://analytics.hathitrust.org/). HTRC Analytics enables non-profit research and educational uses of materials in the HathiTrust collection, including those still under copyright. Specifically, the [Extracted Features](https://analytics.hathitrust.org/datasets) contain metadata about volumes and pages alongside part-of-speech-tagged tokens and token counts extracted from full texts.

With this textual data, I performed sentiment analysis using three tools: VADER, TextBlob, and AFINN. Each tool assigns sentiment scores to input texts which can be aggregated and visualized to show how emotional valence shifts across the span of pages in each book.

[Read the full research project](https://telicity13.github.io/digital-humanities/sentiment_analysis_research_hathitrust.html)
