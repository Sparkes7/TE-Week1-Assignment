## Implemented:

Semantic HTML elements (header, nav, section, footer etc.)
absolute-positioned elements
Flexbox containers in various places
Background images with correct file paths.
Hover states
Transitions
Social media icons using Font Awesome
Embedded a video
Smooth scrolling
'Back To Top' button
Custom font
Background music with the controls.
Javascript that sets music to 15% on page load for UX

## Reflection

The first weeks assignment was to build out a website using HTML and CSS while meeting the user stories requirements of the website. I feel like I've got a solid grasp on everything we have learned so far and have managed to build a website that I'm actually proud of. There are a lot of things that I think went well and was able to implement all of the features from the user stories including the stretch goals.

## What went well

I was able to implement the hover states as per what we learned during our workshops. Additionally, I read about the transition property on MDN for fading to the hover state, and the translate property for some small interactivity.

Adding the social media icons was difficult at first as I wasn't sure on the best way to approach it. One of the resources I found was on w3schools in which they link to an icon pack called 'font awesome', which was easy to get working without having to paste svg elements in the HTML due to the external stylesheet with classes which are already defined.

One of the goals to add smooth scrolling was much easier than I thought it would be. As it turns out, I discovered that there is a css property that handles this for you. This was a common theme throughout building the website as I also thought it would be harder than it was to add music or importing a custom font.

A problem that I ran into when adding the music is that I was able to get the music to start automatically using the autoplay attribute, but the volume was defaulted to 100% which I found to be a negative to the user experience.
I tried to look for attributes that would help me set the default volume, but to no avail. I managed to find out that the audio object has a volume property and decided to use javascript to select the audio element and set the volume to 15% when the page loads so that the music isn't blasting in the users ears.

## What didn't go well

Given that the website doesn't have any real functionality at this point, I tried to focus on the UI/UX and I'm happy with how it looks, however the websites biggest problem is that it is designed specifically for a 1080p display. The website completely falls apart when looking on a phone. There are many reasons for this, one being the lack of relationship in scaling between the background images of the sections and the absolute-positioned text. There is also a problem

Another part of the project which I felt could have been managed better was my stylesheet. As more elements and classes were added, the more CSS rules are then created in the stylesheet and was unsure on how to manage all of the rules - whether I should put them in the order the elements appear on the HTML page, or if there is perhaps another way. It is likely that the number of css rules is normal, however because this is the biggest page I've created, I could see how the stylesheet can become very hectic in the end.

Resources used:
https://developer.mozilla.org/en-US/docs/Web/CSS/transition
https://developer.mozilla.org/en-US/docs/Web/CSS/translate
https://www.w3schools.com/icons/fontawesome_icons_intro.asp
https://www.w3schools.com/icons/fontawesome_icons_brand.asp
https://developer.mozilla.org/en-US/docs/Web/CSS/scroll-behavior
https://www.w3schools.com/jsref/prop_audio_volume.asp
