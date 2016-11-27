---
layout: post
title: Pillars of Prototyping
category: Theories
tags: [webdev, theory, talk]
---
How do you get the best value out of your prototypes? How do you better discuss what you are trying to achieve? Over the years of working with rapid iterative prototyping I have come up with a few core pillars that define what a prototype is and show the best way to use them.
<!-- more -->

A prototype is anything that you can test, anything that you can experiment with to achieve a goal.
The concept of a prototype sounds nice and easy, but the scope is broad, and like most things it's easy to get lost in. People like to think that they are interchangeable, but there is a lot of knowledge and research in making the right prototype as in making it, and the direction you choose to go can have a huge effect on your end goal.

## Consider a more tangible case.
hardware manufacture is much more defined in this case, the steps that go from concept to final product are expensive and well trodden, so the terminology is much better known and understood, looking at their methodology what are the major steps?

### Concept
You think, you plan, you draw, you model. In essence this is already your first prototype, you are testing that what you want is possible, that it should in theory fit physically in the same space, and in more advanced modes simulate physics etc. You already can get the essence of your project, the look and feel, the approximate complexity, colours and shapes. What you are missing the the tangible and visceral, the scale, the weight, real world tests.
At this steps you solve all the really obvious problems, can show people and get an OK, but to get into the real testing you need to build something real.

### Works like
From your concept you know what you are likely to need for the project to work. You build your circuits in breadboards, hook up all the wires and see if it works as planned, refine, test and generally work out if the physical matches the planned. You get an immediate functional test, you can work on any embedded software that is needed, proof of concept for teh functional tests. Again though this is limited in its use, you cant see the final shape or form or test it properly in situ, you need to build the body correctly.

### Looks like
Make the shell, make the right materials for the look and feel. Test the molding process and the ergonomics of the design. This is the point where you can do all of your real-world testing for strength, ergonomics, testing with users and see the final look and feel of the product. What it doesn't do is work at all, this is just the molding, you can pretend to press buttons but it wont respond at all. So what now?

### Combine works-like/looks-like
Like it sounds, this is the combined deal, put the electronics in the case and test it. Just hope it all aligns. You can now do full integration tests, try things in real world tests and get final refinements to how the system goes together. Final tests with users etc. and get regulatory approval before moving on to the finalised molding processes.

As you see, all these prototypes are dealing with different deals of complexity, different realms of adjustability and most of all different specialties in production. Why give a coder the job to create the molds? Given all of this, what parallels can we pull to the digital age?

# Welcome to the internet
There is a disturbing trend to both not prototype enough, and that which is prototyped is done for the wrong reasons or in the wrong scope. Think about the big picture, what your goals are and then imagine your best outcome. Remember: prototypes are there to be helpful and cheap to test.
The most important thing to remember is you have to balance adaptability for scalability, veracity for speed and depth for time.

# The pillars of prototypes
Out of all prototypes there are several standard things, and a few that may or may not apply, bear in mind all of these when you are taking about prototypes, enforce what you are taking about, is this a looks like proto? A works like? Introduce these to your testers, what the limitations are and what to expect so you don't get questions about why everything is grey on a wireframe and you can dedicate your time to testing what you were aiming to test.


## Looks like
Visual style, how close is this to the real design? Is the colour final, the fonts correct, the spacing pixel perfect…


## Feel like
Mainly for hardware, but can also be for thinking of if you are trying to present in the right context, are you using the right phone, tablet, PC, vr device?


## Respond like
Does it interact correctly? Are your transitions working, states toggling, images parallaxing…


## Sounds like
Do you have audio? Should it have sound, is it the final soundscape, button click, keyboard type, action performed…


## Presents like
Is it in the right format? Are you prototyping in the web but it will be finalised in swift, presenting an app on Invision, even specifically if you are aiming at specific hardware…


## Talks like
The amount of times I've seen things break because copy isn't written until the end. How viable is the text you have, the images you present, the language that you are showing…

Talking about your prototypes with more complexity can show not only what you are aiming to achieve but also examine expectations for the final outcome of this prototyping phase.
Out of this mess just remember that time is money, so spend some in planning and scoping correctly.

# How to think about prototypes
Diving further think of your goals, think about your system as a series of tasks. Find the right tool for your current goals but keep in mind your future, is this going to be something you can continue past the testing phase? When is it too cumbersome to continue with what you are using and go to the next phase? You should also not be too dedicated to your prototype, learn when you have pushed it as far as it will go and move on, very few prototypes are going to go with you all the way through the project, take your learnings and then take them to the next prototype.

## Early prototypes

### Paper prototyping 
Paper prototyping is great in early user tests, but great for coding too, drawing out wireframes, data diagrams, sketching interactions and having 'real sliding panels' can help you discuss what is possible with a team very quickly and get understood. It's not very scalable, it's certainly not visual but it's quick and you can spot a lot of problems early.

* Looks: 1/10
* Sounds: 0/10
* Presents: 0/10
* Talks: 1/10
* Feels: 1/10
* Responds: 1/10

### Clickable hotspots
Invision and similar work on a similar premise but more structured and sharable, in the digital media. Taking pictures and adding clickable hotlinks and jumping navigation make for jumpy if not effective demos for early ideas and user testing. Very flexible and best used with ready wireframe software like sketch or illustrator.

* Looks: 3/10
* Sounds: 0/10
* Presents: 1/10
* Talks: 3/10
* Feels: 1/10
* Responds: 3/10

### Custom tools
Pixate is great for animations and look and feel for demos and presentations for native style apps, but they are fiddly to alter and not hugely scalable in the long run. They are still based on false code and very hard to translate anything into functional end product.

* Looks: 8/10
* Sounds: 2/10
* Presents: 3/10
* Talks: 4/10
* Feels: 2/10
* Responds: 8/10

## With code

### Styleguides
for visual styles think about element sheets, mocked pages and templates, making little or no effort to get anything sensible to fill it. These should be based on the code that you are going to deliver on, and should be examples of live code if possible. Show every button style, every button state, and then add animations. State etc is still needed but should be kept as clean as possible, this is to test the elements independently not the logic of the page as a whole.

* Looks: 5-10/10
* Sounds: 5-10/10
* Presents: 10/10
* Talks: 0/10
* Feels: 3/10
* Responds: 5/10

### Wireframe flows
For interaction think about wireframe elements, filled with placeholder text you should be interested in the flow, the movement between elements, the transitions and the placement on a page, in an app. These should be minimally styled, maximally interactive.

* Looks: 2/10
* Sounds: 2/10
* Presents: 10/10
* Talks: 5/10
* Feels: 6/10
* Responds: 7/10

### Mocked servers
Data systems should be treated carefully and separated with a data abstraction layer, allowing for external data to be stubbed and played with before you get too hooked on trying to get that server to respond correctly. Make a demo server to get more complex setups working, think of meteor to demo quick websockets, throw up servers with 'framework' and stub quick APIs. Making a rest API? Make a server with Swagger. Actually test security settings and monitor responses by bouncing information to live servers through your stubbed API.
Simple solutions like postman might be enough for this if you only want to test a system.
The content of your files should be thought about here too, what are you expecting to get for data, what do you have to do to it to make it look right?

* Looks: 0/10
* Sounds: 0/10
* Presents: 10/10
* Talks: 0/10
* Feels: 0/10
* Responds: 8/10

### Page templates
This should be the final mock before the final elements that brand it a final product. Probably doesn't have final content, but if it does all the better! This should be used for final validity testing before the final polish for launching.

* Looks: 9/10
* Sounds: 9/10
* Presents: 10/10
* Talks: 5/10
* Feels: 9/10
* Responds: 9/10

# Bringing it all together
So you mock a server, throw in some basic styles and make half an interaction model, but what you really needed to test was the client REST API. You really enjoyed trying react native, but your end product needs to be in swift. You have three binders full of paper prototypes for customer tests and an elaborate set of pullies and winches to show your animation.

Everyone gets it wrong sometimes, gets carried away or just gets tunnel vision that what they are doing is the only way to do things. If you remember to examine your goals of your prototypes and what you are trying to achieve you can more easily see when you have exhausted one method and need to try something else.

Think about your last projects, how did your prototypes work? did you maximise their usefulness, or did they become a burden to maintain? By planning your goals and aiming at specific targets you can get the most out of your time and effort.


[https://drive.google.com/open?id=1NN97sR9nx0J0lwu6JjeF3hDCKpB-cMIA7KBP9Nhbdr0](Slides in google slides can be found here)