---
title: Study of the Cmd + Ctrl participant user
layout: post
permalink: hackathon-participant
---

One of the things that I love about working with Security Innovation is the variety and depth of projects that I work on. This one was no different. The Cmd + Ctrl platform is a scoreboard for a ‘hackathon’-styled product that Security Innovation offers.

They’d already built and tested an MVP, but they knew that the design and usability was letting them down. Let’s take a look at why -

![Lack of architecture meant the navigation was convulated and had too many options for users](/assets/images/participant-user/navigation.png)
![Design, language and general aesthetics were inconsistent](/assets/images/participant-user/purchase-hint.png)
![Application lacks structure and well-thought out design](/assets/images/participant-user/user-management.png)

There are fairly major issues with their user experience in their initial product. Basically everything that encompasses the user experience - like user journey, information architecture and usability - is non-existant. That’s why they hired me.

The first step for creating a better and more usable application is to understand the user and to give that user a clear path. For this project, there are 3 types of users:

* User - Participant in Hackathon
* User - Customer Admin (managing participants)
* User - Super Admin (managing all user)

Now these roles and their functionalities were already decided on so it was a simple matter of picking apart the design and working out the best way for any user to get through the application.The images below are taken from my brief for Security Innovation.

![How the participant should move through the application](/assets/images/participant-user/user-journey.png)

The biggest part of designing this application was nailing these workflows. These are the backbone of any usable application because it’s not about what a user sees and is able to do, it’s about when a user sees something and that it’s relevant to the point in their journey. *This* is key. Having a defined journey means certain things can be hidden at different stages with no effect on the user and we can actually make their experience better by doing so.

The next phase was to jump into the design and wireframes.

![Creating the left-hand anchoring early by following a similar pattern on the login/signup page](/assets/images/participant-user/mockup1.png)
![Using the left-hand side as an anchor, where the right hand-side side is the variable. Setting the precedent of table structures and controls from the beginning.](/assets/images/participant-user/mockup3.png)
![Displaying simple data with tables - the way they should be used](/assets/images/participant-user/mockup4.png)
![Similar design patterns creates consistency for the application and helps the user stay oriented](/assets/images/participant-user/mockup5.png)
![Even when controls vary, they remain in the same top-right corner - consistency is key](/assets/images/participant-user/mockup6.png)
![Tabs can be confusing, but having already them used initially for the login/sign up page, I think they're use is fine in this case](/assets/images/participant-user/mockup7.png)

I spent roughly 10 hours coming up with different ideas on loose paper and I kept coming back to this one. For one, the product was always going to be very simple in terms of development - I knew that in any future versions they did, it probably wasn’t going to have a tonne of additions to the navigation and structure of the website. This is why having a side navigation was possible.

Another reason I thought this design would work is because of the nature of the application. It’s a secondary application that runs besides another application - websites that are hackable, where participants can score points for breaking into them and/or finding their vulnerabilities. This scoreboard application needed to be very simple and very easy to use. In my opinion, having a left-hand navigation makes sense in this case as in the Western world, we read from left to right, making the navigation the first thing the user sees. This orients the user but it also creates a comforting anchor on the left-hand side of the screen.

I would also like to discuss my work designing the new user onboard. I always make it my aspiration to design applications that are simple to use and need no tutorial to understand them. However, in this case, I felt that given we had a initial product that was being used by customers already (and we were introducing something completely different), orienting the user in the application was a good idea.

We needed to re-confirm the visual cues in the navigation, so I designed a slider that would give context to those in one sentence or less.

![Prompting the user with visual cues helps make clear the intent of the icons in the navigation before the user needs to use them](/assets/images/participant-user/mockup2.png)

Now, although sliders aren’t fantastic in regards to usability usually, I think in terms of the audience (technically educated users), a slider is fine. As well as this, most users would choose to skip the on-boarding, preferring to jump right in and initiate themselves. As a developer, I know that’s what I do and having conducted user research on many other professional developers, I’ve seen the same thing over and over. The slider is there if you want it, but the application is easy to use on it’s own.

