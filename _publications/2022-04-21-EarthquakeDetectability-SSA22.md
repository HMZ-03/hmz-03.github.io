---
title: "Local Earthquake Detectability Using Long-haul Fiber Cables With DAS Technology"
collection: publications
category: conferences
permalink: /publications/2022-04-21-EarthquakeDetectability-SSA22
excerpt: 'Xiaowei Chen, John McKnight, Yanlan Hu, **Minzhe Hu**, Zefeng Li,Raymond Ng, Pranshu Ratre, Zhongwen Zhan, Deepankar Dangwal and Zhuobo Wang'
date: 2022-04-21
venue: 'SSA 2022 Annual Meeting'
---

[[LINK]](https://seismosoc.secure-platform.com/a/gallery/rounds/29/details/8243)
Over the past decades, distributed acoustic sensing (DAS) has been at the forefront of seismology due to density of sensors. However, due to limitations of the available fiber cables, each DAS array has different sensitivities to ground motion. In summer 2021, we connected a Silixa iDAS interrogator to two long-haul fiber segments (50 km and 66 km, respectively) in Enid, Oklahoma using the first 20 km of each segment. The DAS array is located along a state highway and has pockets of high noise, such as on/off ramps.

In this study, we use 47 local earthquakes from the OGS catalog that located are within 30 km of the DAS arrays to examine the relationship between detectability on DAS array and event information.

Initial waveform inspection shows that local traffic signal is mostly above 10 Hz, while local earthquakes have broader frequency range. For each earthquake, we compute RMS (root-mean-square) for each trace before and after low pass filter below 8 Hz and then visually scan the waveform and RMS images. As a result, we identify 27 out of the 47 events on the DAS array. Among the 27 events, 11 are visually observable without filter due to their proximity to the array, while the other events require filtering to be separated from local traffic.

These 47 events are distributed within 8 separate spatial clusters according to the OGS catalog. Our next step is to apply automatic picking algorithm to extract windowed waveforms for the 27 events that are visually detected on DAS array, then use them as templates to scan through continuous waveform via waveform cross-correlation and stacking to detect other events in each cluster.

We will further analyze the relationship between signal quality and energy on the DAS array and event source information (i.e., magnitude, distance, azimuth, focal mechanism). We will also compare the signal between the DAS array and collocated nodal arrays for selected events. These efforts are expected to better understand the sensitivity and detectability of the DAS array along a noisy state highway.