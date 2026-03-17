+++
title = 'On Resolution'
date = 2026-03-20
draft = false
tags = ['blog']
teaser = "I've been caught on this as of late."
+++

Resolution for many modern developers is an obstacle to abstract away from, rather than an element that directly affects all design. If you work with pixel art and point-filtered 3D, abstraction of resolution, really, is not an option. Thus, it becomes an essential decision at the start of a project to choose a suitable resolution for one's goals.

For me, however, I am thinking less at a project-by-project scale, and more on a studio scale, so the idea would be to determine a resolution for *all* projects. This is why it is so important to me. All tooling, art rules, etc. would be formulated around this resolution, allowing the studio to focus more on what I care to *experiment* with the most—story and design—and allow mastery rather than experimentation in visuals.

So with this value of definition understood, I've spent quite some time considering what resolution might be most suitable for TABLEAUX THEORY.

I've known from the start that 16x9 would be the ratio, as this is the standard for the vast majority of modern screens, so this at least gives us a place to start. But what resolution?

Given that the highest modern, generally universally compatible resolution is 1920x1080, I thought it might be interesting to utilize this and do "high res pixel art". This would also give me the option to play with smaller visuals on screen, which I found quite appealing. The problem is, on smaller screens, these smaller visuals become uninteresting. Since I think of Modern Visual Novels as functioning best as personal, handheld experiences, this higher resolution would not make sense. At least not for the primary product line. Also, the lack of obscuring of imperfections in 3D environments meant that a much higher portion of dev time be spent on 3D asset development, which seems contrary to studio goals.

When I decided on the resolution for mvn-sd, *Everything I Know, and Everything I'm Ever Gonna Know*, I considered what would be the best low resolution option that would natively scale to both 1280x720 and 1920x1080. This was 640x360. This resolution, like all resolutions, has its pros and cons. It is quite excellent in the sense that a skilled developer truly can feel as though they have control over every pixel on screen. Any resolution even a bit larger than this, and it is inevitable that certain pixels will be uncontrolled. Additionally, the lower resolution practically forces "mental pixels" from the concept of "for every pixel shown on screen, one is taken from the user's mind". This is a core philosophy of the studio. I love to prompt the user's imagination rather than show information directly.

The downside is that there truly is a limit to the amount of information shown on screen, as well as the inability to have fully "cartoon anime" characters such as *ENA* or *Z.A.T.O.*, which is my preferred art style. With 640x360, we actually have to imply said art style rather than present it.

So, with the desire for more room and this particular art style, I gave a shot to 960x540. I don't see too many projects that use this resolution, but it maps well onto most monitors 1920x1080 or higher (4k, etc.), and it seemed to be a nice middle ground where pixels would still be crunchy enough, but still allow me room.

But then something hit me.

Wait, the aforementioned art style implication and limitations on information may be a boon rather than a bane. Again, any increase in resolution is going to be additional work for artists. Filling a screen with meaningful systems takes a special kind of designer, not to mention user, and even if the designer is capable of filling up a pixel-perfect screen with enough design information it indefinitely requires an exponential amount of work, especially when considering that all systems in one screen will hopefully affect the others.

And I took a step back. Yes, I quite like the idea of producing 960x540 modern visual novels, but I don't believe this is correct for the primary product. In addition to the simplicity benefits from 640x360 mentioned, 960x540 also rather contains the same problem of allowance of too much information for handhelds as 1920x1080 does. Perhaps some day I will create a second line of "deluxe"\* modern visual novels designed for larger screens rather than handhelds, but I just can't help but believe we've found our perfect resolution for primary products in 640x360.

---

\*Probably will have a better name than "deluxe".
