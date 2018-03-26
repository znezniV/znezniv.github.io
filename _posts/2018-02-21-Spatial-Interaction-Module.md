---
layout: post
title:  Spatial Interaction Module Journal
date:   2018-02-21 14:21:56 +0100
categories: ZHdK Blog
permalink: spatial-interaction-journal
desc: A journal about the "Spacial Interaction Module" at Zurich University of Arts
---

This post is a journal for the module "Spatial Interaction" at Zurich University of Arts in the fourth semester of the Interaction Design course. 

Together with BirdLife Switzerland Students of our course are working together in groups with the aim to create an interactive exhibition about bird songs.

## 21.02. Wednesday – Visiting BirdLife
Today, our class met each other in the morning to visit BirdLife in Riedt bei Neerach where Switzerland's second largest bird reservation is located in a marsh. However, compared to other countries it is reasonably small, only about one square kilometer. 
![The mesh of BirdLife in Riedt bei Neerach ]({{ site.url }}/assets/posts/spatial-interaction/mesh.jpg)

The BirdLife center offers an exhibition space, wooden paths in the marsh and huts to hide and observe the birds. Even the path to the huts is covered so the birds don't get startled. Everything is made that nature and the birds won't be disturbed too much by people by also keeping it possible to watch them.

The huts to observe the birds are rather small, contain three benches and folded horizontal window slots which should be opened slowly and carefully to not startle the birds. But done right, the birds won't notice their observers. Equipped with binoculars, there is a view on the pond, the shore on the other side and some small (probably artificial) islands for the birds. Unfortunately, besides ducks, there wasn't a lot to see on this day but it was very interesting anyway. And I like ducks.
![Windows slots ]({{ site.url }}/assets/posts/spatial-interaction/window-slots.jpg)

Afterward, we were able to take a look at the exhibition space and ask some questions to our partner of the project. This will help us a lot in the further project and for an exhibition, it is crucial to know the environment we are working for.

At the end and after a short food and coffee break (which was very friendly form BirdLife), we were able to listen to a presentation about the nightingale of Valentin Amrhein, a researcher of this bird. It was highly interesting to hear about his research. He and his team observed the behavior of nightingales, how they mate and build their territory. All this is connected with the singing of the males. They attract the females with a total amount of 200 different songs and mark their territory which they keep for their whole life. Also, males are very active during the night and in the morning dawn. There are theories why especially in the morning dawn but still no real evidence.
Also, the presentation contained how researchers, analyze songs and calls, how birds generate sounds, why some species learn songs of other species and why they even sing and call in general. Very interesting.

## 22.02. Tuesday – Zoo of Zurich
This day started very excitingly when we met in the morning to go to the Zoo of Zurich. 

First of all, we visited the room with tropical birds which was more or less an open room with filled with tropical plants. We were able to see various birds singing or doing calls. The great thing was that we had two experts with us which could explain us some more about the birds. They explained to us that there are birds which are constantly communicating with other birds of their species and others that are just more about singing not that regularly. They also told us that usually, birds are waiting for other species to finish before the call or sing which was fascinating for me.

We then continued in the Masuala Hall, which is a huge tropical building filled with various animals, from birds, monkeys, bats, turtles, chameleons and so much more I could list here. Since it was not my first visit, it still was very interesting to see how the place was built to enable people to see animals in a bit more free and surrounding way than usual without disturbing the animals too much. If it really works out might is another question.
![Masuala Hall]({{ site.url }}/assets/posts/spatial-interaction/masuala-hall.jpg)
![Bird in the Snow]({{ site.url }}/assets/posts/spatial-interaction/bird-in-snow.jpg)

However, it was way harder to discover and distinguish the different birds from the call since the place was much bigger and way noisier. Also, when we asked visitors about their impression with the bird songs they were aware that the sounds were here but they could not make sense out of them.

## 23.02. Friday – Brainstorming

This day, we first had tech-input about mapping with a projector where we learned to map with processing but also with Resolume Arena 6. It was very interesting and could help us to realize our projects.

However, we first had to figure out the actual project to work in the following weeks. To get many great ideas in short amount of time, our mentors prepared a morphologic raster with fields of birdsong topics and interaction design topics.

So then, we split up in two groups sitting in pairs in front of each other and continued with brainstorm speed dating were after three minutes we had to cycle through the rows and change our brainstorm partners.

After a short time, we had many new ideas, chose one we were the most interested and split up into groups we will continue the next week. 
![No ideas there]({{ site.url }}/assets/posts/spatial-interaction/empty-papers.jpg)
![Many ideas here]({{ site.url }}/assets/posts/spatial-interaction/filled-papers.jpg)
![Jerome ready for the project]({{ site.url }}/assets/posts/spatial-interaction/ready-jerome.jpg)

## 27.02. Tuesday – Getting Deeper
After the weekend and theory Monday, we sat together in the group to deepen the concept of our project.
Of course, we already had the idea in mind from the brainstorm speed dating. But we still wanted to discuss openly other ideas and how we felt about the initial idea. So to start with, we discussed what is important for us, what we want to focus on and — since we are very privileged in this school — what would be the most fun for us to work on. Since the final project should be displayed in an exhibition, we wanted to give at least a little value to the project in the sense to be a little educative but also not to close to traditional education "fun" software we knew from our own childhood. Also, our project partner of BirdLife said that for them it would be the most important to get people into the fascination of birds.
![Cute people discussing]({{ site.url }}/assets/posts/spatial-interaction/discussion-initial-idea.jpg)
![Description of Initial Concept]({{ site.url }}/assets/posts/spatial-interaction/initial-concept.jpg)

After discussing some other interesting ideas, we came back to our initial idea, a game of the male nightingale, which try to expand and defend their territory and attract females.
We talked about the real basic general properties of the game but also about some more detailed technical things.

### Game Concept Idea
The game should be based on multiple players on an interactive table where visitors are able to act as the male nightingale and compete against each other to grow and defend their territories. Then we thought about to create a table with a transparent surface that displays a projection from the inner bottom of the table as we have seen it from reacTIVision projects. Each player owns a block which they can place on the table and their projected bird follows it in a few seconds of flying. The table is divided into small parts of territories which have to be occupied or stolen from other birds by flying there first and solving a short riddle about bird songs. The bird that has the biggest territory (either after a certain time or reaching an amount of "points") wins. Rival birds can fend off by flying into the part of their own they are going to lose.
Of course, the riddles should relate to bird songs and could be solved by listening, whistling or just entering input by hand.
![Initial Sketch of the Table]({{ site.url }}/assets/posts/spatial-interaction/sketch-table-initial.jpg)  

#### Technical View
##### Table
As mentioned, we thought of a table that is able to display a projection from a projector located inside of the bottom of the table. The controller could be a block with a fiducial code attached to the bottom where a camera can track their position below, also located below the table.
![Ideas how to divide the map]({{ site.url }}/assets/posts/spatial-interaction/sketch-map-division.jpg)  

##### Block
If possible and if we want to work with rich input such as whistling and sound, the bricks should include a microphone and speakers so everything is in a small individual device. By hand interactions like turning or moving graphical input could be controlled.

##### Map
The map should contain random points of the center of the parts of the territories which could be divided with a Voronoi algorithm.

We are aware that this probably is too much to do. But the next day, we have the chance to ask our mentors about their opinion. Not just technically but also conceptually through their experience. Maybe we are lucky and there are easy ways to solve that.

## 28.02. Wednesday – Mentoring and Early Game Concept
This morning we had the chance to get a mentoring from our docents. Our main questions were what they would suggest as a success measuring in the game if they form their experience think it would be realistic to do it technically and of course what their overall opinion to the idea is.

### Mentoring
They were quite happy with our idea and reminded us that at the end of the module we don't have to be finished but rather have a somehow working prototype. Also, they kept us realistic that if we work on a game, the first version probably will a bit boring and need some refinement. But at the same time, we shouldn't spend all the time in only perfecting the game concept in this module. At the end of the five weeks, it should be possible to present the potential of our idea.
Also, they helped us by highlighting the interesting aspects of the nightingale and their territory "fight". It's in particular interesting that they look for the territory in morning dawn and that other than other animals the males don't fight for their territory by smashing their head against each other but by singing.
![Eary Game Concept]({{ site.url }}/assets/posts/spatial-interaction/sketch-game-concept.jpg)

### Game Concept
So, back on our work we first discussed how we wanted to continue with our project. After the lunch, we first did some research on scientific facts about the territorial nightingale singing to refine a story we wanted to tell in the game. Also, we did some research on other existing games.
![Dogs vs. Cats]({{ site.url }}/assets/posts/spatial-interaction/research-existing-games.jpg)

So we wrote a short abstract of the story of the game and also a brief rule description. We plan to refine and expand these rules after prototyping together on the following day. 

#### Connection to Reality

##### Morning Dawn
The game starts to conquer new or defend pre-establishment territories.

##### Sunrise
(Game duration is limited from morning dawn until sunrise)
The game will be "won" if one bird's territory is the biggest when the game is finished. The leading player will be marked with a fictional female nightingale to add a strategic extra layer.

##### Night
(The day fast-forwarded until the night)
The winning bird successfully expanded his territory and sings until the female flies to him.

### Preparing For the Next Day 
Since we had some time left, we wrote down what we want to achieve the next day. 

Of course, first, in the morning we have to participate the tech-input. Later we want to paper-prototype the game to refine and expand rules for the games. Therefore, we already prepared some questions we want to answer.

For Friday we then have to prepare a short presentation as well.

## 01.03. Thursday – Preparing for the Presentation
In the morning we had a tech-input for MaxMSP with some synthesizers. The goal was to learn how we could synthesize the sounds of the birds and automate them.

For the afternoon we mainly focused on preparing the presentation on the following morning. 
Presentations are very practical because they also force us to nail down our ideas. Often ideas are very clear for us in our mind but if you have to explain it to somebody else in a very short time forces to consider even small details.

We knew that we wanted a block with a fiducial code on the bottom to be our controller. Also, the game was mainly defined but the thing that we did not really define was how the short exercises in the game will be. So we brainstormed again.

One idea to mimic a bird song with whistling into a microphone attached to the controller block. Another was to select from a pool of songs and then try to create new combinations with them at each tree the bird wanted to expand his territory. Our final idea was to create another version of "Simon Says" where you have to replay bird song sample combination which increases in difficulty. This was also the idea we then presented.

![Block Controller]({{ site.url }}/assets/posts/spatial-interaction/sketch-block-controller.jpg)
![Preparing Presenation]({{ site.url }}/assets/posts/spatial-interaction/preparing-presentation.jpg)

## 02.03. Friday - Presentation and Blind Spot
This day started right away with presentations in front of the whole class, our mentors and the people from BirdLife Switzerland. Also, a few interns joined the presentation.

We were surprised that after our presentation there was almost no feedback from our audience what we did not define as a good sign. We were not sure if the concept was even clear if people like it or not, which was a bit unexpected and disappointing. As a general feedback from Stephan of BirdLife was that our class was way to visual and should focus more on the birdsong itself.

We then took the chance to get an individual feedback from our mentors. And this time, in our opinion, this was very successful. They enabled us to see a blind spot that we really kept really stick with that game idea which was not necessary at all. The idea to interact with the bird songs itself was very interesting alone. Also, a bit more exploratory way of explaining the territories instead of creating a full game. 
This really helped us a lot and so we agreed on focusing on the manipulation of the bird songs with the block on the table.

## 06.03. Tuesday - Continuing the Concept
We first started to sit together and present each other the ideas we had thought of over the weekend. They actually fit very to each other.
![Morning Meeting]({{ site.url }}/assets/posts/spatial-interaction/morning-brainstorm.jpg)

We then noticed that it would help us a lot if we have something in our hands to prototype. And indeed it increased our discussion a lot.

The first idea, was to have an exploratory way were one bird block was positioned on the table and some song particles placed next to it which will be played randomly. The bird with the most blocks obviously is the one with the most complex song and therefore also more powerful in the territory fight.
![First Prototype]({{ site.url }}/assets/posts/spatial-interaction/prototype1.jpg)
 
In the second idea, we and only continued with the particles that could be stacked on each other. After that, we went to the interaction design lab to ask them for a technical idea to realize it.
![Second Prototype]({{ site.url }}/assets/posts/spatial-interaction/prototype2.jpg)
![Stack Prototype]({{ site.url }}/assets/posts/spatial-interaction/stack.jpg)

In parallel to the prototype, we contacted our expert Valentin Amrhein for help and if he has a collection of nightingale sounds. Another person in our group did some initial tests on a technical level to play around with the fiducial trackers and a webcam we borrowed from the lab.

## 07.03. Wednesday - Continuing the Concept
When we met today in the morning we sat together and started to discuss the project.
We quickly came to the conclusion that we were not happy with where it was going to and decided to develop further. We mainly wanted to shift the focus more on the songs itself. 

We started to get the idea from discussion while drawing and then prototype a very dumb version just to make it possible to touch the elements, better communicate and faster realize what works or not in a very early stage.

Our new idea was to make a puzzle game with the song. Therefore the users need to take parts of the song and fit it together. Each part is a block (with a fiducial at the bottom) which contains the audio of the sound will then be played from left to right (x-axis) to play the full song. The position of the block on the y-axis we imagined to be the pitch of the part. We were sure that we need to do more research on this and maybe rethink if it makes sense and if there's a way that probably is better connected to the nightingale topic.
![Sketch Sequencer]({{ site.url }}/assets/posts/spatial-interaction/sketch-sequecer.jpg)
![Editing Keyboard Mapping]({{ site.url }}/assets/posts/spatial-interaction/editing-keyboard-mapping.jpg)

First, we took advantage of the prototype during our discussions, tested it with ourselves afterward and finally on other persons.

## 08.03. Thursday - Refining the Prototype 
This day we started to think about the project individually while one person of our group started to figure out how to prototype with the fiducials which we did the whole week but never made it work. In the end, it was the webcam that was somehow not working with the reacTIVIsion software which should be able to recognize the markers then. Another camera made its job and finally enabled us to work with the technology we actually want to use.

Before we were able to continue much further with the prototype we had a mentoring with our sound docent of the interaction design department. One of his critics was that he wasn't sure what the game should people tell which we could explain with the story we wrote beforehand. We want to show the life of a male nightingale and how his songs improve. Another thing, which we were also considerate was the categorization of the song parts which was a bit arbitrary. Our mentor suggested us to not spend too much time on thinking about it and just ask our nightingale specialist Valentin.

In Valentin's reply from our mail, he suggested us to categorize into Alpha, Beta, Gamma and Omega sound. It took us a while to find out what it means but a few DuckDuckGo search queries creates miracles. 

##### Alpha
Little Volume.
##### Beta
Louder, more complex patterns.
##### Gamma
Element repetition, more aggressive (trill).
##### Omega
A _not_ repeated element.

On prototype side, the afternoon enabled us to attach the camera on a tripod, glue some fiducial codes on styrofoam blocks and add sounds on events when a fiducial disappears from the camera field in Processing. This will help us further in our following tests when we want to get deeper feedback on the interaction. If you grab a block now you will cover the code and so let Processing play a sound because the fiducial disappears. 

![Prototyp Fiducial]({{ site.url }}/assets/posts/spatial-interaction/prototype-fiducial.jpg)

## 09.03. Friday - Finalizing the Concept
Friday was highly focused on finalizing the concept of the previous day. Especially about details.

So again here, we split into a group that was focusing on the concept and one person that was working on the technical implementation of the prototype.

The concept group started to bring down the concept to paper and start to draw initial sketches of the interface. Also here, the sketch contains a short explanation of the scientific theory behind the kind of puzzle. From left to right samples should be placed in chronological order and from top to bottom in the various categories of the nightingale songs (alpha, beta, gamma, omega). The users need to sort the songs in correct order of the categories by listening to the samples but the order inside of the samples inside of the categories doesn't matter.
![UI Sketch]({{ site.url }}/assets/posts/spatial-interaction/sketch-first-ui.jpg)

In a further step we tried to align the story in our mind into levels of the life of a bird starting as a baby copying from their close environment, practice new songs in Africa in the winter, young male that wants to impress the females and as older mated nightingale that randomly sings and tries to defend his territory.
![Notes Levels]({{ site.url }}/assets/posts/spatial-interaction/sketch-levels.jpg)

Even first ideas were collected how a tutorial should be implemented to guide our users in a straightforward way.
![Notes Tutorial]({{ site.url }}/assets/posts/spatial-interaction/notes-tutorial.jpg)

In the afternoon, finally, the table arrived where want to project our visuals and place and track the blocks with the fiducials. The box is rather simple. A matt transparent plexiglass board on top, inside infrared lights directed to the inner side of the plexiglass, a camera with a filter that only let pass infrared light and a lot of space for the projector. Basically, the infrared light will be reflected from the top plexiglass only if the block with the fiducial is really on the glass because of it is matt. Also, the distance from the fiducial to the camera is constantly perfect which makes it easy to track. 

## 13.03. Tuesday - 
We continued the fresh week with a little bit of planning for the week because time is running.

The concept group continued to answer some new upcoming questions about the concept, defined screens needed to be designed, assembled mood boards and started to design screens that will be discussed and improved the next day. 

We also decided that the tutorial and the first level need to be combined because it will provide a common theme in connection with the story.

As well we had a mentoring in the afternoon were our mentors highlighted that we should not focus on developing a fully working game but rather show the potential and make a good, clear presentation about our idea.

In parallel, we made big steps further with the technical prototype that blocks can be placed and validated from predefined fields. 

## 14.03. Wednesday - Starting With Production
This day's focus was to finally start with the production.
We started to look at the two screens we finished on the day before, discussed the approaches and started to figure out things to improve. Especially, we had to give more consideration to the image that won't be that colorful and with a lot of contrast which makes it hard to display thin, light lines and text of course. But anyway a lot of text won't be great for our future users. We also decided that we want to have a shaded room that our users will be able to focus more on the bird sounds and the display will appear shining brighter.

We then recognized that it is crucial to get more context for which "screen" we're designing for and need to test the projector as soon as possible on the surface. Looking back, this was tougher than expected. We were not sure how and where to attach the projector which a student of the older semester suggested us to use. So we had to ask our former lecturer Moritz Kemper for help how he did that. Kindly, he visited us for some minutes and explained how it works. So first disconnected a plate attached with some screws from the projector and drilled new holes into an aluminum mount which was screwed on a wall inside of the table.
![Preparing to Drill holes]({{ site.url }}/assets/posts/spatial-interaction/drilling.jpg)
From there the projector should have projected on a mirror which then reflected on the inner surface of the table glass. The result was not satisfying at all and after some trials of changing the distance of the mirror to the projector lens, we and our lecturer Joël came to the idea to directly project on the glass. So we put the projector on the inner floor of the table and had a bit more satisfying result. We were very happy that it worked out in such a simple way and only had prevent it from falling down. Glue is our best friend.

Next to the hassle with the projector, we finished the logic of the puzzle. Sometimes things that seem simple can be laborious as well. Thanks and shout out to Aurelian for having a listening ear and working brain to help to fix the code with a single break in the loop. For the next day, we can focus a bit on easy maintenance and performance before continuing with graphics, level logic, and sounds. A lot of work, a lot of fun — hopefully. Thank you, Aurelian, in advance.

As well we continued to work on the visuals for the levels and especially of the tutorial.

## 15.03. Thursday - Production II
We started the new day with a quick planning of the day and reviewing the approaches for the interface. We quickly found things to improve and had some questions arise from our discussion. We also agreed that we need to check a further version of the projection itself which will give us way more context. 

The quality of the projection was not really for our fastidious eyes which are accustomed to very dense pixel display which we use on a daily basis. The pixels are clearly visible, the contrast is not that strong and the distribution from the light of the projection is kind of uneven. But we probably have to live with that. 
However, the experiment to display the interface on the projection helped us to address serval issues such as contrast, approximation/grouping of the elements, and readability of the text. But it also helped us to verify the size of the blocks we finally want to move.
Also, we noticed that the sonogram we initially wanted to take place above the fields for the blocks was taking to much of very important space and does not really serve a purpose. User tests never verified that it helped anyone and at the same time we assumed (but never verified) that it could be a distraction from the sound.
  
As mentioned, in the last day we built a box to lift up the projector to get a smaller better fitting projection on the glass. Unfortunately, the box from the previous day was a little too high and so we had to make a smaller version of it to get the bigger image. 

Later on, we split up tasks into refining the interface, continue to code, organizing the exhibition space and preparing sounds samples. For the next day, we had in mind that somebody will work on making nice looking blocks to move on our table.

With a more or less accurate mapping and working code for the riddles, we were able to play around with the table.

## 20.03. Tuesday - Production IV
The last week and still a lot to do. Last week, we already split up the groups into different fields of responsibility, physical objects, software/digital development and visual design mainly focused on the interface.

For the physical part, the big task was to build the blocks which then will be moved to the table with the fiducial attached at the bottom. Requirements for the block were, that they fit on the table, not damage it and feel good in the hand of the exhibition visitors. Last week we decided to make them round because they fit way better in the hand but also it does not matter if you rotate the block to fit inside of the fields for each song snippet on the table. It just fits. Additionally to the natural feeling of wood, we wanted to give it some extra weight with a metal cylinder inside of the block. This not only makes the block feel more solid, it also assists the fit on the table and makes sure the printed fiducial code is recognized properly. We tried different materials and processes and wanted to finish by the next day.
![Blocks Prototype]({{ site.url }}/assets/posts/spatial-interaction/prototype-blocks.jpg)

For the visual part, it was mainly the completion of all screens that could be displayed in future. Since our work will still be in a state of a prototype at the end, we will need to show that it will have potential in providing a view of the end product. 
Besides the interface, a small part of animations took a lot of time. To reinforce the story of our bird, we planned to work on animations, mostly a bird that is flying around.

On the technically part, we started to enhance the mapping of the blocks which are recognized by the camera. Also, we made functions that made it able to map sounds and fields, played the correct sample when lifted, validated if the block was on the correct field or not and played the full self-arranged song when all blocks were placed correctly. There is still a long way to go but it is getting closer to the final idea.
![Validation Function Prototype]({{ site.url }}/assets/posts/spatial-interaction/prototype-validation.jpg)

## 21.03. Wednesday - Production V

### Physical
After we took decisions about how we wanted to build the blocks, we want into production. And as always this cost much more time than expected. But finally, we finished all the elements we wanted to use.

### Visual
Finally, all the screens were done and we continued to work on the animation. Therefore we also took the presentation into consideration because we wanted to present directly on the table and technically it was not possible to code all the things and the tutorial for the prototype. So we decided to keep it as a slide that will be displayed a prototype on the table before we switch to the actual prototype as a demo.

### Technically
Already yesterday, we recognized that the mapping of the blocks was not satisfying. Because of the fisheye sense of the camera inside of the box which recognizes the fiducial all the position of the blocks were shifted a bit. To fix that, our mentor Joël highlighted a paragraph in the reacTIVision documentation, that we need to calibrate the camera first before we continue to work. Therefore we needed to print a huge grid out of paper, place it on the top of the table so that the camera was able to see and then manually calibrate the fisheye away. And it worked so well.

![ReacTIVision Calibration]({{ site.url }}/assets/posts/spatial-interaction/calibration.jpg)

After that, we reminded the collision detection of the field and the block. Later, we removed the projection of the block which helped us to identify were the recognized position of the block was. After a few unintended tests of our pushy and impatient colleagues, we recognized that since we removed the visual guidance, there needs to be a feedback if the block was placed on the field. Thanks to them! Quickly we added states of "empty", "occupied", "correct" and "wrong" with a colored border around the field. The latter two were only displayed when all the fields were occupied by a block. What also changed and was in our initial plan was that now the validation only happens when all the fields are occupied. Also, you only see the wrong fields but you need to find out where they should be placed which could be way more difficult whenever the visitors have more than two wrong snippets. This makes them listen more carefully again. 
After implementing the final sounds, we added all the further static visuals so we can review, polish and finalize the prototype the next day.

## 22.03. Thursday - Preparing Presentation
This journal entry is rather short because there were many small things to fix.
First of all, we had to figure out how we wanted to make the presentation on the table. Since we got the information to only talk five minutes and give a five minutes demo, we decided to keep the explanation and process low and just start with the product itself in the tutorial. This part was not finished in the prototype so we faked it in Keynote. All videos, animations, and sounds will be played after acting like we were using the desk as a touchscreen.

After building up in the exhibition room, we had a short breakdown because nothing of the tracking of the blocks was working. After some panic and discussion, we figured out that we just had to calibrate again. 

## 22.03. Friday - Presentation and Conclusion
We met early in the morning to practice our presentation to raise the quality of it and give a better impression of the project.

The presentation went very well and it was a lot of fun seeing all the other exciting projects in our class.

We gathered very valuable feedback and ideas from our classmates and mentors which we will definitely consider if we can continue with the project. 

![Moving Block on Table]({{ site.url }}/assets/posts/spatial-interaction/presentation1.jpg)
![Validation Wrong]({{ site.url }}/assets/posts/spatial-interaction/presentation2.jpg)
![Validation Correct]({{ site.url }}/assets/posts/spatial-interaction/presentation3.jpg)

### Conclusion
We very pretty happy with the project we did. It was quite simple but powerful at the same time. We learned a lot in every field. 