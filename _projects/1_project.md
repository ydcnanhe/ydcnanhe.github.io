---
layout: page
title: DUET-ISR
description: A blind source separation algorithm separating any number of sources with two (or more) microphones
img: assets/img/DUET_ISR_cover.jpg
importance: 1
category: work
related_publications: true
---

## Introduction
<hr>

Humans are born with selective hearing ability. Algorithms that simulate this function can be of great help in many applications in noisy environments, such as hearing aids, voice assistants, hands-free communication, teleconferencing, and humanoid robots with auditory systems.

<div class="row justify-content-sm-center">
    <div class="col-sm-3 mt-3 mt-md-0">
        {% include figure.html path="assets/img/voice_assistant.jpg" title="bss application 1" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-3 mt-3 mt-md-0">
        {% include figure.html path="assets/img/hand-free_communication.jpg" title="bss application 2" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-3 mt-3 mt-md-0">
        {% include figure.html path="assets/img/conference_call.jpg" title="bss application 3" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-3 mt-3 mt-md-0">
        {% include figure.html path="assets/img/humanoid_robot.jpg" title="bss application 4" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Some application scenarios that a speech separation algorithm may provide help in noisy (multiple people) environments.
</div>

***DUET-ISR*** is such an algorithm that we proposed to realize speech separation. It has the following advantages:

- **Versatility**: can separate any number of speakers using just two mictrophones.
- **Simplicity**: a simple processing structure, first masking, then spatial filtering. Utilizing two basic spatial cues, time delay and amplitude attenuation.
- **Robustness**: good separation performance under reverberant environments.
- **Analyzability**: non-deep learning framework, a completely analytical algorithm.
- **Convinience**: can be used directly, no need to train.

## Demo
<hr>

We show an example when we try to separate four speakers' speeches in the reverberation of 130 ms. We only show one mixture (in total two) and one demixed signal (in total four).

[source](http://ydcnanhe.github.io/assets/audio/project1/2mix4src130ms_sources_1.wav)

[mixture](http://ydcnanhe.github.io/assets/audio/project1/2mix4src130ms_mixtures_mixture1.wav)

[demix](http://ydcnanhe.github.io/assets/audio/project1/2mix4src130ms_duet-isr_demixed1.wav)


More demos and comparison with other algorithms can be found [here](https://ydcnanhe.github.io/demo-icassp2022/).



## Code
<hr>

Matlab code is available [here](https://github.com/ydcnanhe/codes-icassp-2022). This repo also contains other blind source separation algorithms.

<hr>
Reference:

He, Yudong, He Wang, Qifeng Chen, and Richard HY So. "Harvesting Partially-Disjoint Time-frequency Information for Improving Degenerate Unmixing Estimation Technique." In ICASSP 2022-2022 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP), pp. 506-510. IEEE, 2022.
