---
layout: post
title: Why the background-color is peach
description: 
date:   2022-07-22 19:58:00 +0000
tags:   [accessibility]
---

The background colour of this website is <code>#EDD1B0</code>, a light peach hue. Why this specific colour?

<b>TLDR;</b> its easier for most people to read black text on this colour, which decreases reading time.

## Research

As with anything where you want an answer grounded in the scientific method, you turn to academic research and peer reviewed papers. A paper titled <i>'Good Background Colors for Readers: A Study of People with and without Dyslexia'</i>[<a href="#1">1</a>] lead me down this path. My aim is for this website to be content-first, free from distraction, extremely quick load times and easy to read. A good background colour is the foundation.

The authors, Rello, L., and Bigham, J. of Carnegie Melon in the US, tested the readability and comprehension of text on 10 different colour backgrounds with 341 people, with the aim to see how different colours affected people's ability to read and understand text. 89 of the participants had dyslexia, a condition characterised by difficulties with word recognition, poor spelling and word decoding abilities. The remaining participants did not have any known specific learning difficulties. You can read about the research methodology in the article.

## Colour Choices

The ten colours discussed in the research article are distinct and designed for black text:

<table class="styled-table">
    <thead>
        <tr>
            <th>Colour</th>
            <th>RGB</th>
            <th>HEX</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Blue</td>
            <td>(150,173,252)</td>
            <td>#96ADFC</td>
        </tr>
        <tr>
            <td>Blue Grey</td>
            <td>(219,225,241)</td>
            <td>#DBE1F1</td>
        </tr>
        <tr>
            <td>Green</td>
            <td>(168,242,154)</td>
            <td>#A8F29A</td>
        </tr>
        <tr>
            <td>Grey</td>
            <td>(216,211,214)</td>
            <td>#D8D3D6</td>
        </tr>
        <tr>
            <td>Orange</td>
            <td>(237,221,110)</td>
            <td>#EDDD6E</td>
        </tr>
        <tr>
            <td>Peach</td>
            <td>(237,209,176)</td>
            <td>#EDD1B0</td>
        </tr>
        <tr>
            <td>Purple</td>
            <td>(185,135,220)</td>
            <td>#B987DC</td>
        </tr>
        <tr>
            <td>Red</td>
            <td>(224,166,170)</td>
            <td>#E0A6AA</td>
        </tr>
        <tr>
            <td>Turquoise</td>
            <td>(165,247,225)</td>
            <td>#A5F7E1</td>
        </tr>
        <tr>
            <td>Yellow</td>
            <td>(248,253,137)</td>
            <td>#F8FD89</td>
        </tr>
        
    </tbody>
</table>

## Results

After their testing, the researchers found in both the group of people with dyslexia and the group without any specific learning difficulties, peach to be the easiest colour to read. See the figure below showing a <a href="https://en.wikipedia.org/wiki/Candlestick_chart" target="_blank">candlestick chart</a> (Wikipedia link) of the different colours on the x-axis and reading time on the y-axis.

<figure>
	<img src="/images/posts/2022/background-color-readability-dyslexia.jpg" alt="."/>
	<figcaption>Fig. 1: Reading time for the dyslexic group.</figcaption>
</figure>

<figure>
	<img src="/images/posts/2022/background-color-readability-control.jpg" alt="."/>
	<figcaption>Fig. 2: Reading time for the control group.</figcaption>
</figure>

You can also see in the chart above, peach has the least variance between participants indicated by the box surrounding the average line. In contrast, colours such as Green and Blue Grey have larger boxes indicating a greater variance.

## Key findings

<ul>
	<li>Background color has a positive impact on text readability for people with dyslexia and people without specific learning difficulties.</li>
	<li>Warm background colours, such as peach, orange, and yellow increase readability.</li>
	<li>Cool background colours, such as blue grey, blue, and green decrease readability.</li>
</ul>

## Final words

Consider how you can improve the readability of your website and focus on your content. What steps could you take to help your users?

## References

<ol>
	<li id="1">Rello, L., and Bigham, J. (2017) <a href="https://dl.acm.org/doi/abs/10.1145/3132525.3132546" target="_blank"><i>Good Background Colors for Readers: A Study of People with and without Dyslexia</i></a>. [Accessed July 2022].</li>
</ol>
