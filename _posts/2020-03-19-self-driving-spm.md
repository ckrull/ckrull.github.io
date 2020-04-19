---
layout: post
title: AI for nanoscience microscopy
subtitle: Automating Scanning Probe Microscopy 
bigimg: /img/cover_3D_flame.jpg
tags: [projects]
---

[Scanning Probe Microscopy](https://en.wikipedia.org/wiki/Scanning_probe_microscopy) (SPM) is a powerful surface characterisation technique, that has revolutionised many scientific fields ranging from nano-science to biology. Its ability to resolve structures down to the level of individual atoms has led to many impressive insights and a [nobel prize](https://www.nobelprize.org/prizes/physics/1986/summary/).  But SPM is more than that, it is also a tool to manipulate individual atoms to create any desired shape for example to write letters, quantum objects or create [movies. ](https://www.youtube.com/watch?v=oSCX78-8-q0)

However, these feats come at a price. Operation of an SPM is not straightforward and requires expertise and  impressive amounts of patience.  Maintaining an SPM probe in good working conditions can be very tedious. This  process, usually performed by the human experimentalist, and rarely reported, has been called [*soul destroying repetition*](https://www.nature.com/articles/d41586-018-03305-2). We  recently [published]((https://www.nature.com/articles/s42005-020-0317-3))  a machine learning framework that can to operate an SPM autonomously. It intelligently detects arising issues and repairs them without the need for human supervision. 

This system, dubbed DeepSPM,  can operate and acquire optimal SPM data autonomously, for multiple  days straight,  without any human supervision.

The advance bridges the gap between nanoscience, automation and artificial intelligence (AI), and firmly establishes the use of machine learning for experimental scientific research. DeepSPM brings advanced SPM methodologies such as atomically-precise nanofabrication and high-throughput data acquisition closer to a fully automated turnkey application. The  [framework](https://github.com/abred/DeepSPM) is publicly available  as open source, creating an important resource for the nanoscience research community. 

Crucial to the success of DeepSPM is the use of a self-learning agent, as the correct control inputs for SPMs are not known beforehand. Learning from experience, our agent adapts to changing experimental conditions and finds a strategy to keep the system stable.

Our [study](https://www.nature.com/articles/s42005-020-0317-3) demonstrates fully autonomous, long-term SPM operation for the first time by combining:

- an algorithmic approach for sample area selection and SPM data acquisition;
- supervised machine learning using convolutional neural networks for quality assessment and classification of SPM data, and
- deep reinforcement learning for dynamic automated in-situ probe management and conditioning.

###### THE STUDY

*[Artificial-intelligence-driven scanning probe microscopy](https://www.nature.com/articles/s42005-020-0317-3)* was published in *Communications Physics* in March 2020.

Researchers at Monash University’s School of Physics and Astronomy worked closely with collaborators at the [Max Planck Institute of Molecular Cell Biology and Genetics](https://www.mpi-cbg.de/home/) (Dresden), [Max Delbrück Center for Molecular Medicine](https://www.mdc-berlin.de/) (Berlin) and [Heidelberg University](https://www.uni-heidelberg.de/en).

All experiments were performed at Monash, partly funded by the [Australian Research Council](https://www.arc.gov.au/). Computations were performed at the [Center for Information Services and High Performance Computing](https://tu-dresden.de/zih?set_language=en&cl=en) (European Research Council funded).

(the image shows a nanoscopic image of [single metal organic molecules](https://www.nature.com/articles/nmat3547) imaged with a SPM system)