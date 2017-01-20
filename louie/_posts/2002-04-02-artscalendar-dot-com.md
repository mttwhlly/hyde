---
layout: post
title:  USER-FOCUSED EVENT SITE REDESIGN
author: Matt Whalley
category: 
img: http://mttwhlly.github.io/louie/assets/images/artscal-glamour.png
---

<div class="column green" markdown="1">
![Glamour shot](http://mttwhlly.github.io/louie/assets/images/artscal-glamour.png)
</div>

### BACKGROUND  
<span class="intro__p" markdown="1">
[ArtsCalendar.com](http://ArtsCalendar.com) is an established South Florida arts & cultural events site. It is highly trafficked & receives a steady flow of event submissions from active users who range from individual artists or small galleries to renowned performing arts venues & internationally acclaimed festivals. </span> 

¶ Over the years, pages & features were added to the site by those maintaining it without much thought into whether it was beneficial (or even necessary) for the users. If the site were a house it may be a candidate for the show *Hoarders* - it was time for an intervention because of love for the valuable site hidden underneath all of the unintentional [dark UI](http://darkpatterns.org/), inconsistent styles & confusing redundancies. 

¶ Recent grant funding afforded the [Broward Cultural Division](http://broward.org/arts) & [ArtServe](http://www.artserve.org/) - owners & operators of the site - to finally invest time & resources into turning Arts Calendar into a community-driven tool for artists & art-lovers alike. For art lovers, it could be a simple & delightful event-finding experience. For artists & venues, a simplified, engaging means to promote upcoming events. There is even the longer-term potential of incorporating a marketplace (e-commerce) component! But I'm getting ahead of myself since we haven't even fully gotten through the research phase yet.  

### RESEARCH 

#### Heuristic Evaluation   

¶ The house needed cleaning (& fixing)...and this first step was an exercise in being ruthlessly honest about the good (like the intentions of offering a great service to the community), the bad (terribly confusing links & buttons) & the ugly (a clip art logo, for example). Seriously considering who the site's users are (and new demographics we wished to reach with a redesign), it was necessary to intentionally steer all conversations among stakeholders & team members away from topics like colors, new logos & "let's make the site look like X-trendy-site dot com" that could easily stray into subjective arguments the vision wasn't clear enough at this point to sustain. 

<small>Mobile & desktop versions of existing site</small>
<div class="column green" markdown="1">
![Glamour shot](http://mttwhlly.github.io/louie/assets/images/artscal-before.png)
</div>

<small>Mobile app for video sharing before redesign</small>
<div class="column green" markdown="1">
![Glamour shot](http://mttwhlly.github.io/louie/assets/images/fruio-before.png)
</div>

¶ I evaluated the user experience of each page, taking note especially of pain points in user journeys. I spoke with several users to get more insight into problems I may have overlooked. The notes were consolidated into a report (the report was created using Matt D. Smith's [AIUX](https://rwd.aiux.co/) method which I cannot recommend highly enough if you're into UX design) that I presented along with existing & revised sitemaps & low fidelity wireframes based on these findings. The objective at this stage was to take a high level view & begin setting a solid architectural structure in place. This would set the foundation for all future discussions on form & function that would best accomplish the goals of the site. We had numerous meetings to refine this broad vision & to condense it down into what we felt comfortable was all we needed initially to deliver a great experience to our audience.

### ORGANIZING & PLANNING

#### Sitemapping & User Flows

¶ Creating user profiles, sitemaps & flows that would help them get from their point A to point B in as delightful of a way as possible is one of my favorite parts of the job. A lot of consideration was also taken at this stage to research the national & international market for others providing similar services. We looked to find what was done well and on what we could improve through our project. Many meetings, revisions & thoughtful discussions were had at this stage.

<small>Optimized sitemap</small>
<div class="column green" markdown="1">
![Sitemap](http://mttwhlly.github.io/louie/assets/images/artscal-sitemap1.png)
</div>
<small>User flow (for member)</small>
<div class="column green" markdown="1">
![Sitemap](http://mttwhlly.github.io/louie/assets/images/artscal-flow1.png)
</div>
<small>User flow (for guest)</small>
<div class="column green" markdown="1">
![Sitemap](http://mttwhlly.github.io/louie/assets/images/artscal-flow2.png)
</div>

#### Wireframing

¶ In order to make the vision of the site/app real to everyone on the team & stakeholders, I got into wireframing & creating interactive prototypes as quickly as I could. As mentioned before, lo-fi Wireframes were built using Adobe Illustrator & the AIUX method while high-fidelity wireframes/interfaces were created using [Sketch](https://www.sketchapp.com/). 

<small>Event app wireframes</small>
<div class="column green" markdown="1">
![Sitemap](http://mttwhlly.github.io/louie/assets/images/artscal-wire1.png)
</div>
<small>Video app wireframes</small>
<div class="column green" markdown="1">
![Sitemap](http://mttwhlly.github.io/louie/assets/images/artscal-wire2.png)
</div>
<small>Prototype screens in Sketch</small>
<div class="column green" markdown="1">
![Sitemap](http://mttwhlly.github.io/louie/assets/images/prototype1.png)
</div>

#### Prototyping

¶ For prototyping I used [Framer](https://framer.com/) for micro-interactions & [Marvel](https://marvelapp.com/) to view how the app/site could work as a whole. A number of meetings were held in which feedback was openly taken & incorporated into revisions until a strong, agreed-upon prototype was arrived at.

#### Interface design & CSS style guides

¶ The stakeholders ultimately chose to go with a WordPress-based app/site. In order to assure the final product would be as close as possible to agreed upon mockups, I wrote custom CSS for the visual styles. Testing of the CSS was done using [Codepen](http://codepen.io).

##### Typography
¶ When it came to the artscalendar.com project, selecting a typeface was particularly enjoyable as it afforded me the opportunity to survey the market & relevant fonts our target demographics would readily associate with arts & then to find something within those constraints that would communicate the voice we wanted artscalendar.com to have. Our final choice for the web was [Karla](https://fonts.google.com/specimen/Karla), a font designed by Jonny Pinhorn for Google. 

<div class="column green" markdown="1">
![Karla](http://mttwhlly.github.io/louie/assets/images/karla.png)
</div>

¶ The logic behind this decision began by narrowing our options down to grotesque sans-serifs - widely used in the arts community & neutral enough to allow the content to be front & center. This provided us with a lot of amazing options to explore but for practicality reasons, self-served webfonts & subscription-based services were ruled out to avoid a lapse were administration to change leaving the best option to go with Google fonts. Out of the fonts Google offers, Karla struck a good balance between having a pleasant personality & being sturdy & somewhat impartial in the grotesque tradition. 

##### Color

¶ In an effort to express sophistication & cleanliness as well as focusing on elevating content, the colors black & white were selected as the main palette. Bright gradients reminiscent of the neon lights characteristic of South Florida were included subtly to tie the look & feel together.

UPDATE: This project is currently in development but if you'd like, you can take a [sneak peek](http://wpdev22.artsopolis.com/). Stakeholders decided to hold off on developing a mobile app for the time being in favor of converting the site to a progressive web app. 

Launch is slated for the week of January 23, 2016.