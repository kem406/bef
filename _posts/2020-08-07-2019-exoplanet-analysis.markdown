---
layout: post
title: "2019 Exoplanet Analysis"
img: flashlight.jpg # Add image post (optional)
date: 2020-08-07 12:52:00 +0300
description: Page for exoplanet analsysis on 2019 star observations. # Add post description (optional)
tag: 
---

# Goal

The purpose of this project is to learn how to analyze the light curve of a star using the transit method to detect exoplanets, and distinguish true exoplanet transits from false positives created by NEBs (nearby eclipsing binaries). To accomplish this goal, [Allyson Bieryla](https://www.cfa.harvard.edu/~abieryla/) provided us with two datasets from 2019: one with an exoplanet, and another with a false positive. Our goal is to determine which is which. 

## Why Exoplanets?

Exoplanets are crucial to our understanding of the universe. After all, we live on a planet ourselves! Discovering new exoplanets can help us learn:

* How planets (like Earth) form 

* How different celestial objects interact

* Whether other places in the universe could have life

Right now, there are 4,197 confirmed exoplanets. TESS has confirmed 66 of those planets, but also has 2,120 more candidates.

## Why Use the Transit Method?

The transit method of exoplanet detection is arguably the most efficient method of currently available.

* There are a total of 4,197 currently confirmed exoplanets. The transit method has discovered 3,187 of these.

* Transit is very good for showing specific information about a planet’s size, atmosphere, temperature, and more.

* A previous transit-based mission, Kepler, had already proved successful and informative, having discovered 2,342 planets. 

Latex test:

<img src="https://render.githubusercontent.com/render/math?math=e^{i \pi} = -1">

Quote test: 

> Hi. <cite>- Lorem Ipsum</cite>

# Transit Method Overview

The transit method for detecting exoplanets is as follows:

## Step 1: TESS Observation

![TESS](https://kem406.github.io/bef/assets/img/tess.jpg | width=250)
<sub>Source: NASA</sub>

The [Transiting Exoplanet Survey Satellite](https://tess.mit.edu/) (TESS) is a NASA mission led by MIT dedicated to the discovery of extrasolar planets. TESS determines exoplanet candidates and predictions from data sent back to the ground. It accomplishes this by doing the following:

* TESS surveys the sky through four cameras. The sky is split in 26 parts, each of which is observed for 27.4 days.

* TESS watches for transiting planets, which means it watches for planets that pass between the satellite (the observer) and the host star.

* TESS sends data to be analyzed and reviewed so that exoplanet candidates can be recorded.



## Step 2: Target Selection

We select targets based upon certain criteria, then send them in for observation at the Fred Lawrence Whipple Observatory.   

## Step 3: Data Reduction and Analysis in AstroImageJ

Using AstroimageJ, we analyze the data we get from our observations, culminating in a transit lightcurve.

## Step 4: Conclusions

Based on our data analysis, we decide whether the target could still be an exoplanet candidate, or if it’s a false positive.
