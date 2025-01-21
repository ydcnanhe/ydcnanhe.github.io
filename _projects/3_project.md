---
layout: page
title: Denoising in Low SNR Environment
description: An algorithm for clear conversation in noisy environments
img: assets/img/construction_site.jpg
importance: 3
category: work
---
## Introduction
<hr>

An algorithm that can make a conversation clearer in very noisy environments, such as construction sites and airports. In such environments, the sound is relatively weaker and typically drowned out by noise, which is known as **low signal-to-noise ratio (SNR)**. This algorithm can help us better communicate in such environments. Details can be found in my [PhD thesis](http://ydcnanhe.github.io/assets/pdf/thesis.pdf).

<div class="row justify-content-sm-center">
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/construction_site.jpg" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Two workers on a chocolate construction site. How can they communicate easily in the presence of loud pile driver noise?
</div>

## Demo
<hr>

We simulated a scenario where a male and a female were speaking while their voices were drowned out by the sound of pile driver's engine. After processing with our algorithm, we can clearly hear their talking. The algorithm used three microphones. The number of microphones is free to be reduced or increased (at least two).

[noisy sound](http://ydcnanhe.github.io/assets/audio/project3/noisy_sound.wav)

[processed sound](http://ydcnanhe.github.io/assets/audio/project3/processed_sound.wav)
