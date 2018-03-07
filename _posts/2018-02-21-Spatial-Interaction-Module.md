---
layout: post
title:  Spatial Interaction Module Journal
date:   2018-02-21 14:21:56 +0100
categories: ZHdK Blog
permalink: spatial-interaction-journal
desc: A journal about the "Spacial Interaction Module" at Zurich University of Arts
---

This post is a journal for the module "Spacial Interaction" at Zurich University of Arts in the forth semester of the Interaction Design course. 

Together with BirdLife Switzerland Students of our course are working together in groups with the aim to create an interactive exhibition about bird songs.

## 21.02. Wednesday – Visiting BirdLife
Today, our class met each other in the morning to visit BirdLife in Riedt bei Neerach where Switzerland's second largest bird reservation is located in a marsh. However, compared to other countries it is reasonably small, only about one square kilometer. 
![The mesh of BirdLife in Riedt bei Neerach ]({{ site.url }}/assets/posts/spatial-interaction/mesh.jpg)

The BirdLife center offers an exhibition space, wooden paths in the marsh and huts to hide and observe the birds. Even the path to the huts is covered so the birds don't get startled. Everything is made that the nature and the birds won't be disturbed to much by people by also keeping it possible to watch them.

The huts to observe the birds are rather small, contain three benches and folded horizontal window slots which should be opened slowly and carefully to not startle the birds. But done right, the birds won't notice their observers. Equipped with binoculars, their is a view on the pond, the shore on the other side and some small (probably artificial) islands for the birds. Unfortunately, besides ducks there wasn't a lot to see at this day but it was very interesting anyways. And I like ducks.
![Windows slots ]({{ site.url }}/assets/posts/spatial-interaction/window-slots.jpg)

Afterwords, we were able to take a look at the exhibition space and ask some questions to our partner of the project. This will help us a lot in the further project and for an exhibition it is crucial to know the environment we are working for.

At the end and after a short food and coffee break (which was very friendly form BirdLife), we were able to listen to a presentation about the nightingale of Valentin Amrhein, a researcher of this bird. It was highly interesting to hear about his research. He and his team observed the behavior of nightingales, how they mate and build their territory. All this is connected with the singing of the males. They attract the females with a total amount around 200 different songs and mark their territory which they keep for their whole life. Also males are very active during the night and in the morning dawn. There are theories why especially in the morning dawn but still no real evidences.
Also, the presentation contained how researchers, analyze songs and calls, how birds generate sounds, why some species learn songs of other species and why they even sing and call in general. Very interesting.

## 22.02. Tuesday – Zoo of Zurich
This day started very exciting when we met in the morning to go to the Zoo of Zurich. 

First of all we visited the room with tropical birds which was more or less an open room with filled with tropical plants. We were able to see various birds singing or doing calls. The great thing was that we had two experts with us which could explain us some more about the birds. They explained us that there are birds which are constantly communicating with other birds of their species and others that are just more about singing not that regularly. They also told us that usually birds are waiting for other species to finish before the call or sing which was very fascinating for me.

We then continued in the Masuala Hall, which is a huge tropical building filled with various animals, from birds, monkeys, bats, turtles, chameleons and so much more I could list here. Since it was not my first visit, it still was very interesting to see how the place was built to enable people to see animals in a bit more free and surrounding way than usual without disturbing the animals to much. If it really works out might is another question.
![Masuala Hall]({{ site.url }}/assets/posts/spatial-interaction/masuala-hall.jpg)
![Bird in the Snow]({{ site.url }}/assets/posts/spatial-interaction/bird-in-snow.jpg)

However, it was way harder to discover and distinguish the different birds from the call since the place was much bigger and way noisier. Also, when we asked visitors about their impression with the bird songs they were aware that the sounds were here but they could not make sense out of them.

## 23.02. Friday – Brainstorming

This day, we first had tech-input about mapping with a projector were we learned to map with processing but also with Resolume Arena 6. It was very interesting and could help us to realize our projects.

However, we first had to figure out the actual project to work on the following weeks. To get many great ideas in short amount of time, our mentors prepared a morphologic raster with fields of birdsong topics and interaction design topics.

So then, we split up in two groups sitting in pairs in front of each other and continued with brainstorm speed dating were after three minutes we had to cycle through the rows and change our brainstorm partners.

After a short time we had many new ideas, chose one we were the most interested and split up into groups we will continue the next week. 
![No ideas there]({{ site.url }}/assets/posts/spatial-interaction/empty-papers.jpg)
![Many ideas here]({{ site.url }}/assets/posts/spatial-interaction/filled-papers.jpg)
![Jerome ready for the project]({{ site.url }}/assets/posts/spatial-interaction/ready-jerome.jpg)

## 27.02. Tuesday – Getting Deeper
After the weekend and theory Monday, we sat together in the group to deepen our concept about our project.
Of course, we already had the idea in mind form the brainstorm speed dating. But we still wanted to discuss openly other ideas and how we felt about the initial idea. So, to start with we discussed what is important for us, what we want to focus on and — since we are very privileged in this school — what would be most fun for us to work on. Since the final project should be displayed in a exhibition, we wanted to give at least a little value to the project in sense to be a little educative but also not to close to traditional education "fun" software we knew from our childhood. Also, our project partner of BirdLife said that for them it would be the most valuable to get people into the fascination of birds.
![Cute people discussing]({{ site.url }}/assets/posts/spatial-interaction/discussion-initial-idea.jpg)
![Description of Initial Concept]({{ site.url }}/assets/posts/spatial-interaction/initial-concept.jpg)

After discussing some other interesting ideas, we came back to our initial idea, a game of the male nightingale, which try to expand and defend their territory and attract females.
We talked about the real basic properties of the game but also about some more detailed technical things.

### Game Concept Idea
The game should be a multiplayer on an interactive table where visitors are able to act as the male nightingale and compete against each other to grown and defend their territories. There we thought about to create a table with a transparent plate to that display a projection from the bottom. Each player owns a block which they can place on the table and their projected bird follows it in a few seconds of flying. The tables is divided into small parts of territories they have to occupy or steal from other birds by flying there first and solving a short riddle about bird songs. The bird that has the biggest territory (either after time or reaching an amount of "points") wins. Rival birds can be fend off by flying into the part of their own they are going to lose.
Of course, the riddles should related to bird songs and could be solved by listening, whistling or just entering input by hand.
![Initial Sketch of the Table]({{ site.url }}/assets/posts/spatial-interaction/sketch-table-initial.jpg)  

#### Technical View
##### Table
As mentioned, we thought of a table that is able to display a projection from a projector located below the table. The controller could be a block with a fiducial code attached to the bottom where a camera can track their position below, also located below the table.
![Ideas how to divide the map]({{ site.url }}/assets/posts/spatial-interaction/sketch-map-division.jpg)  

##### Block
If possible and if we want to work with rich input such as whistling and sound, the bricks should include a microphone and speakers so all is in a small individual device. By hand interactions like turning, more graphical input could be controlled.

##### Map
The map should contain random points of the center of the parts of the territories which then can be divided with a Voronoi algorithm.

We are aware that this probably is to much to do. But the next they we have the chance to ask our mentors about their opinion. Not just technically but also conceptually through their experience. Maybe we are especially lucky and there are easy ways to solve that.

## 28.02. Wednesday – Mentoring and Early Game Concept
This morning we had a the chance to get a mentoring from our docents. Our main questions were what they would suggest as a success measuring in the game, if they form their experience think it would be realistic to do it technically and of course what their overall opinion to the idea is.

### Mentoring
They were quite happy with our idea and reminded us that until the end of the module we don't have to be finished but rather have somehow working prototype. Also, they kept us realistic that if we work on a game, the first version probably will a bit boring and will need some refinement. But at the same time we should spend all the time in only perfecting the game concept in this module. At the end of the five weeks, it should be possible to present the potential of our idea.
Also they helped us by highlighting the interesting aspects of the nightingale and their territory "fight". It's in particular interesting that they look for the territory in morning dawn and that other than other animals the males don't fight for their territory by smashing their head against each other but by singing.
![Eary Game Concept]({{ site.url }}/assets/posts/spatial-interaction/sketch-game-concept.jpg)

### Game Concept
So, back on our work we first discussed how we wanted to continue with our project. After the lunch we first did some research on some scientific facts about the territorial nightingale singing to refine a story we wanted to tell inside the game. Also we did some research on other existing games.
![Dogs vs. Cats]({{ site.url }}/assets/posts/spatial-interaction/research-existing-games.jpg)

So we wrote a short abstract of the story of the game and also a brief rule description. We plan to refine and expand these rules after prototyping together in the following day. 

#### Connection to Reality

##### Morning Dawn
The game starts to conquer new or defend pre-establishment territories.

##### Sunrise
(Game duration is limited from morning dawn until sunrise)
The game will be "won" if one birds territory is the biggest when the game is finished. The leading player will be marked with a fictional female nightingale to add strategic extra layer.

##### Night
(The day fast-forwarded until the night)
The winning bird successfully expanded his territory and sings until the female flies to him.

### Preparing For the Next Day 
Since we had some time left, we wrote down what we want to achieve the next day. 

Of course, first in the morning we have to participate the tech-input. Later we want to paper-prototype the game to refine and expand rules for the games. Therefore, we already prepared some questions we want to answer.

For Friday we then have to prepare a short presentation as well.

## 01.03. Thursday – Preparing for the Presentation
In the morning we had a tech-input for MaxMSP with some synthesizers. The goal was to learn how we could synthesize the sounds of the birds and automate them.

For the afternoon we mainly focused on preparing the presentation on the following morning. 
Presentations are very practical because they also help us to nail down our ideas. Often ideas are very clear for us in our mind but if you have to explain it to somebody else in a very short time forces to consider small details.

We knew that we wanted a block with a fiducial code on the bottom to be our controller. Also the game was mainly defined but the thing that we did not really define was how the short exercises in the game will be. So we brainstormed again.

One idea to mimic a bird song with whistling into a microphone attached to the controller block. Another was to select from a pool of songs and then try to create new combinations with them at each tree the bird wanted to expand his territory. Our final idea was to create another version of "Simon Says" where you have to replay bird song sample combination which increase in difficulty. This was also the idea we then presented.

![Block Controller]({{ site.url }}/assets/posts/spatial-interaction/sketch-block-controller.jpg)
![Preparing Presenation]({{ site.url }}/assets/posts/spatial-interaction/preparing-presentation.jpg)

## 02.03. Friday - Presentation and Blind Spot
This day started right away with presentations of the whole class in front of our mentors and the people from BirdLife Switzerland. Also, a few interns joined the presentation.

We were surprised that after our feedback there was almost no feedback from our audience what we did not define as a good sign. We were not sure if the concept was even clear, if people like it or not, which was a bit unexpected and disappointing. As a general feedback from Stephan of BirdLife was that our class was way to visual and should focus on the bird song itself.

When then took the chance to get an individual feedback from our mentors. And this time, in our opinion, this was very successful. They enabled us to see a blind spot that we really kept really stick with that game idea which was not necessary at all. The idea to interact with the bird songs itself was very interesting alone. Also, a bit more exploratory way of explaining the territories instead of creating a full game. 
This really helped us a lot and so we agreed on focusing on manipulating the manipulation of the bird songs with the block on the table.

## 06.03. Tuesday - Continuing the Concept
We first started to sit together and present each other the ideas we had thought of in the weekend. They actually fit very to each other.
![Morning Meeting]({{ site.url }}/assets/posts/spatial-interaction/morning-brainstorm.jpg)

We then noticed that it would help us a lot if we have something in our hands to prototype. And indeed it increased our discussion a lot.

The first idea, was to have an exploratory way were one bird block was positioned on the table and some song particles placed  next to it which will be played randomly. The bird with the most blocks obviously is the one with the most complex song and therefore also more powerful in the territory fight.
![First Prototype]({{ site.url }}/assets/posts/spatial-interaction/prototype1.jpg)
 
In the second idea, we get rid of the bird block and only continued with the particles that could be stacked on each other. After that, we went to the interaction design lab to ask them for an technical idea to realize it.
![Second Prototype]({{ site.url }}/assets/posts/spatial-interaction/prototype2.jpg)
![Stack Prototype]({{ site.url }}/assets/posts/spatial-interaction/stack.jpg)

In parallel to the prototype we contacted our expert Valentin Amrhein for help and if he has a collection of nightingale sounds. Another person in our group did some initial tests on a technical level to play around with the fiducial trackers and a webcam we borrowed from the lab.



