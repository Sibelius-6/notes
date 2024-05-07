---
layout: post
title: AMATH 351
description: "ODE 2"
date: 2019-05-01 00:00:00+0000
term: Spring 2019
subject: amath
latex: /pdf/1209/amath351.pdf
image: "/crs_banner/am351.png"
---

The notes above is Fall 2020 version. [Here](/pdf/1195/amath351.pdf) is the spring 2019 version.

Both set of notes are mostly following the textbook/coursenote. Below is a proof of a result.

Some good properties that prof assumed we know (maybe we don't) from previous courses:

<span>&#92;[\mathcal L[tf(t)] = -{d\over ds}\mathcal L[f] &#92;]</span>

Proof:
<span>&#92;[
&#92;begin{aligned}
{d\over ds} F(s) &= {d\over ds} \int _ 0^\infty e^{-st} f(t)dt &#92;&#92;
&= \int _ 0^\infty {d\over ds}e^{-st}f(t)dt &#92;&#92;
&= \int _ 0^\infty -t e^{-st}f(t)dt &#92;&#92;
&= -\int _0 ^\infty e^{-st}(tf(t))dt &#92;&#92;
&= -\mathcal L [tf(t)]
&#92;end{aligned}
 &#92;]</span>
