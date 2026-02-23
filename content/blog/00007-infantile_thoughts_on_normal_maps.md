+++
title = 'Infantile Thoughts on Normal Maps'
date = 2026-02-28
draft = true
tags = ['blog']
teaser = "Atleast I'm thinking about it."
+++

I've been making myself more open to new rendering styles. I can confirm, my next project will natively be in 1920x1080p. This, if you are using any sort of interpolated filtering, would mean very little. However, since I am dedicated to point filtering, meaning that every pixel is in my control, this change in rendering affects my entire pipeline. I intend, however, for 1920x1080 (or, close to it if aspect ratios change) to be my default going forward. It is seemingly the highest widely used modern ratio that still retains the easy visibility of individual pixels.

This is just one of the many areas that I've updated after the production of *Everything I Know, and Everything I'm Ever Gonna Know*. 

The area that I've been most surprised by is in my deep dive into physically based rendering.

Given that I don't use a pre made engine, it has not been a given that I have access to physically based rendering by default. I'd earlier dismissed it as it felt "too complicated" for minimalist graphics philosophy. However, as I've been reconsidering so much — I've decided to use runtime lighting, for instance — and as it is industry standard at this point, I decided to give it a shot.

<!--TODO: Talk about your findings.-->

![no normals.](/blog/00007-no_normals.png)

![normals and height.](/blog/00007-normals.png)

<!--TODO: Talk about intentional use, such as in persona 5 or 3 reloaded.-->

---

