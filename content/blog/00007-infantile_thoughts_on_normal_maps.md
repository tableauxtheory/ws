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

Given that I don't use a pre made engine, it has not been a given that I have access to physically based rendering by default. I'd earlier dismissed it as it felt "too complicated" for minimalist graphics philosophy.

I tried to things. First, just runtime lighting, which looks like this:

![no normals.](/blog/00007-no_normals.png)

And... I really like it! The novel I'm working on now uses the same locations at different times of day, so rather than creating fully disparate assets for each time, I knew runtime lighting would be a great time saver if I could cause it to not make my gut feel bad.\*

Well, if I liked this, perhaps I would like full PBR as well?

Well...

![normals and height.](/blog/00007-normals.png)

Now, you look at that, and, yes, it does indeed have a feel of "higher production value", but it definitely *does* make my gut feel bad. I just don't like it. The style is just... Muddy. It feels like uncontrolled mess, losing its feeling of authorial intent.

On the abstraction axis — realistic to symbolic — this falls far too into the realistic for my taste. In my art, I certainly like my organic material — humans, plants, etc. — to be more on the symbolic side than my inorganic, but the inorganic materials still need to be somewhat symbolic. Not purely pushing towards realism, that is. It hits this weird space where everything is close enough that any imperfections (which will exist) make things feel wrong... The suspension of disbelief is lost, I think?

You know, I'm not entirely certain why this bothers me. Would love some thoughts. If you see this, and are have thoughts on this sort of thing, reach out via phil@tableauxtheory.com.

---

\*I have a thing where certain artistic decisions make my gut hurt... Maybe should write about this more fully in a different blog.
