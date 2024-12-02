---
title: "CloudTracks: A Dataset for Localizing Ship Tracks in Satellite Images of Clouds"
collection: publications
category: manuscripts
permalink: /publication/2024-01-25-cloudtracks
excerpt: 'Keywords: Data-Centric AI, Computer Vision, Satellite Imagery, Climate Change'
date: 2024-01-25
venue: 'Oral presentation, AI-Driven Innovations in Earth and Climate Sciences, Conference of the American Geologists Union'
slidesurl: 
paperurl: 'http://ahmed14974.github.io/files/cloudtracks.pdf'
citation: 'Chaudhry, Muhammad Ahmed et al. (2024). &quot;CloudTracks: A Dataset for Localizing Ship Tracks in Satellite Images of Clouds&quot; <i>AI-Driven Innovations in Earth and Climate Sciences, Conference of the American Geologists Union 2024</i>.'
---
<img width="1082" alt="image" src="https://github.com/user-attachments/assets/fe6c2602-49f7-4746-9a64-7df39597d8ec">

Clouds play a significant role in global temperature regulation through their effect on planetary albedo. Anthropogenic emissions of aerosols can alter the albedo of clouds, but the extent of this effect, and its consequent impact on temperature change, remains uncertain. Human-induced clouds caused by ship aerosol emissions, commonly referred to as ship tracks, provide visible manifestations of this effect distinct from adjacent cloud regions and therefore serve as a useful sandbox to study human-induced clouds. However, the lack of large-scale ship track data makes it difficult to deduce their general effects on cloud formation. Towards developing automated approaches to localize ship tracks at scale, we present CloudTracks, a dataset containing 3,560 satellite images labeled with more than 12,000 ship track instance annotations. We train semantic segmentation and instance segmentation model baselines on our dataset and find that our best model substantially outperforms previous state-of-the-art for ship track localization (61.29 vs. 48.65 IoU). We also find that the best instance segmentation model is able to identify the number of ship tracks in each image more accurately than the previous state-of-the-art (1.64 vs. 4.99 MAE). However, we identify cases where the best model struggles to accurately localize and count ship tracks, so we believe CloudTracks will stimulate novel machine learning approaches to better detect elongated and overlapping features in satellite images. We release our dataset openly [here](https://zenodo.org/records/10042922).
