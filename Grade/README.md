Thank you for your submission, Will!

WOW WOW WOW! This is a seriously beautiful site!!!
There are lots of great examples of your week-1 learning outcomes and you've produced a wonderfully styled website!! For me, I would not be surprised to see a site like yours being used for professional purposes as it appears currently. It's **that** good (as is the film itself)!!!
There's even a bit of JS for setting the audio volume! You're spoiling us!!!

Let's examine some of your implementations!

## HTML:

I’m a big fan of the way you have structured your HTML file! You’ve followed best practices like including a `<header>`, `<main>` and `<footer>` element and you have nested your other elements inside appropriate containers throughout! The elements you have chosen to use like `<nav>`, `<section>` and `<iframe>` make good semantic sense and also follow some of the best practices we are looking for!

Some things to consider:

- Autoplay audio -> autoplay="true"/loop="true" are boolean attributes. I'd maybe just use autoplay and loop. Many browsers block autoplay by default (thank goodness!) so generally expect to need user-initiated play of audio elements.

## CSS:

Your CSS styling is **really** fantastic for someone at this point in the course! Nicely done!!!
You clearly understand how to use a range of different CSS selectors (and complex selectors!) and are also showing confidence in using layout properties like position:absolute and position: relative, flex and margin/padding.
I really love the strong, consistent theme you've created and those small translation on hover are subtle, but brilliant!.

Some things to consider:

- Fixed header overlap -> The first section (#intro) can hide under the fixed header. You can add a top offset via main { padding-top: `<header-height>`; } and section { scroll-margin-top: `<header-height>`; } to mitigate this.

- Section targeting -> section:nth-of-type(2) applies the background image to the About section, not the hero. If that’s unintentional, swap to a class or #intro.

- Hero image sizing -> .sectionimg has height: 100vh but no width. You can add width: 100%; object-fit: cover; display: block; to avoid distortion and gaps.

- Absolute hero text -> .herobox/.captionbox use fixed pixel offsets; these will often break on small screens. Try using some relative units or a flex/grid overlay.

- 100vh on all sections -> For content-heavy sections, I'd recommend using min-height: 100vh (or let content size naturally) to avoid overflow issues on small screens.

## Reflection:

Thank you for providing such a robust and thoughtful reflection! It’s clear that you’ve carefully considered the successes and challenges that you faced and this will serve you very well as the course continues!

From your reflection:

- 1080p-only layout -> Go mobile-first and avoid absolute positioning for primary layout. Use Flex/Grid, fluid units (rem, %, vw). Add 1–2 media queries (e.g., ~900px, ~600px). For hero overlays, wrap image and the text in a relative container, center with Flex/Grid, and use a subtle gradient overlay for legibility.

- Background images & text overlap: Try to stick to content inside the document flow (not absolutely positioned). If you have to overlay, try to use responsive padding/gaps and max-width containers instead of fixed pixel offsets.

- CSS organisation: My advice is to pick a simple convention and stick to it like:

-- Structure: Base/Reset → Tokens (variables) → Utilities → Layout → Components → Overrides. We haven't introduced these concepts but will make for interesting extra reading.

-- Naming: BEM `(e.g., .card, .card__title, .card--featured).`
https://getbem.com/naming/

-- Practical: Group by component, keep selectors shallow, and add section comments.

- Smooth scroll & fixed header: I'd be keeping html { scroll-behavior: smooth; } and add section { scroll-margin-top: `<header-height>`; } so anchors don’t hide under the header.

## Deployment:

You also successfully managed to deploy your website using Github pages! This is an important achievement and you should be very excited! This is the first of many examples of your great work heading out into the Wide World!

This is an outstanding piece of work and you should be very proud of yourself! We’re definitely proud of you!!
I’m giving you a 4 for this assignment as you have successfully implemented all of the core goals we were looking for but also went on to implement stretch goals!

Truly impressive work this week Will, keep this momentum going!!! Well done!!!

~Joe
