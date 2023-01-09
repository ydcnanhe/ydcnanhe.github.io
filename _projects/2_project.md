---
layout: page
title: Online <br> DUET-ISR
description: An online directional enhancement/denoising algorithm with two (or more) microphones.
img: assets/img/Online_DUET_ISR_cover.jpg
importance: 2
category: work
---

## Introduction
<hr>

Have you ever encountered the following embarrassing situations? You try to make a phone call at a subway station but the surroundings are very noisy. Or you are enjoying your vacation outdoors, listening to the sound of nature but the surrounding conversation is disturbing you. Online DUET-ISR is a **real-time** algorithm you need to get out of these situations. The algorithm can **enhance the sound from the desired direction and suppresses surrounding noise**. Or oppositely, it can **suppress the noise from the pointed direction and remains the surrounding sounds**.

**The algorithm is not based on deep learning and can be analyzed and explained.**

<div class="row justify-content-sm-center">
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.html path="assets/img/directional enhancement.jpg" title="directional enhancement" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.html path="assets/img/directional denoising.jpg" title="directional denoising" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Illustration of the two main functions of Online DUET-ISR. (a) Directional enhancement. (b) Directional denoising.
</div>

## Demo
<hr>

We show an application of this algorithm in a subway station scene. The recording was made with real equipment (two omnidirectional microphones with a distance of about 2 cm) in a real Chinese subway station. In the recording, we can hear a woman (one of our colleagues) repeating "one, two, three, ..., ten" in Chinese. At the same time, we can hear the platform announcement, train running, braking, door opening, door closing and other ambient sounds.

[recording](http://ydcnanhe.github.io/assets/audio/project2/metro_recording.wav)

We apply the directional enhancement function of our algorithm to **enhance the voice** of our female colleague.

[enhanced](http://ydcnanhe.github.io/assets/audio/project2/metro_duetisr_enhanced.wav)

We apply the directional denoising function of our algorithm to **suppress the voice** of our female colleague.

[denoised](http://ydcnanhe.github.io/assets/audio/project2/metro_duetisr_denoised.wav)
