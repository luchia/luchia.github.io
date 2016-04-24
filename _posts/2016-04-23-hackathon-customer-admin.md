---
title: Study of the CMD + CTRL customer administrator
layout: post
permalink: hackathon-customer-admin
---

This is a continuation of my work with Security Innovation on the CMD + CTRL hackathon project. In this case study, you'll see how I developed the Customer Admin user for this application.

To understand where this project began, let's take a look at some screenshots of the existing design for this user -

![Even though the pages are simple and from a usability standpoint, clear in the required action, the design left a lot to be desired](/assets/images/customer-admin-user/manage-instances.png)

![The navigation had a huge amount of options available to the user, many of which could be grouped into related tasks to form an easy to use interface](/assets/images/customer-admin-user/navigation.png)

![One example of a user task that could have been grouped with others](/assets/images/customer-admin-user/register-user.png)

![Another example of a user task that oculd have been grouped with others](/assets/images/customer-admin-user/bulk-register.png)

As always, I love to start a project with a clear journey for the user. This user was, in particular, very simple in terms of the task needed to be completed.

![The customer admin user workflow was simple and made it easy to create a usable design because of it's simplicity](/assets/images/customer-admin-user/user-workflow.png)

In comparison to the [participant user](http://luchia.com.au/hackathon-participant), this user had a much simpler workflow. In fact, a lot of the bases were covered in terms of design, as I had already hashed out a lot of the structural layout of the application for the participant user. It was simply a matter of organising the tasks in the existing application with consistency to the first user.

Unfortunately, the time allowed for this project meant that only one portion (the hackathon participant) could be completed fully. Below is as much as I could get done before my time with the company was finished -

![The customer admin launch pad - easy access for the things they most need to control](/assets/images/customer-admin-user/launch-pad.png)

The user logs in and is immediately greeted with the event launchpad. My reasoning for this relates to the nature of the use of the application. The CMD + CTRL application is used in hackathon instances, where a customer admin will manage players as they compete in an event. While they will ocassionally manage users, the weight of their role specifically revolves around the event they are managing.

From the launch pad, the admin is able to edit any instances of the event. Ideally, I would have liked to remove the repetitive buttons and create a similar workflow as what I had on the original design for the hackathon participant - selecting the instance and controlling it with a row of buttons at the top-right of the table.

![Editing the event](/assets/images/customer-admin-user/launch-pad-edit.png)

Within the instance editor, the user is able to adjust settings for the instance and is able to view what sites are enabled and the event schedule information, all of which are controlled by the super admin. I would have liked to have spent more time consolidating this page design - the two columns to a full-width table below is inconsistent and not as user friendly as I would have liked. I also would have liked to have made it clearer that the event name was an input and it was possible to edit it.

![Managing instances of an event - controlling who can use it and when](/assets/images/customer-admin-user/manage-instances-2.png)

From within the view, you're able to do a few things for the events. Each event will have a number of instances, where it's running on one or more machines. The customer admin is able to launch all instances (a requirement to start an event), terminate all of them (thereby kicking everyone off) or delete an instance (for management purposes).

I particularly like this layout as it goes back to my original participant user design and it's clear and succinct. With a possibility of having hundreds of instances, having an edit/delete/launch button for each instance is unneccessary. If I had it my way, I would have implemented this on all of the pages (which you will see very soon).

![Managing players is no longer an exhaustive series of clicks - simple and easy](/assets/images/customer-admin-user/manage-players.png)

The other actions the customer admin should be able to complete relate to managing users. Similarly to the launch pad, there are excessive links on this page that could have been simplified. I would have liked to had a row of buttons on the top-right hand side of the table, where each user is selectable and able to be managed by those buttons.

![Adding a user](/assets/images/customer-admin-user/add-user.png)

This page was put together very quickly and I don't feel as if it fits the application. If I had more time to complete this project, I would have created a left-hand navigation, similar to the launch pad, where I could manage everything no matter what page I'm on.

The other thing that I like about my work on this user is the navigation. The navigation *very* simple but it's also extremely clear about what the tasks a customer admin can complete. In this respect, I think the application for the customer admin is incredibly simple to use and needs no onboarding or tutorial to get users started with the application. I'm very proud of this.

Overall, this particular user didn't get a lot of time allocated to it with this project as there was a 4 week sprint for the participant user and not a lot of time left over to complete this user. If I were to come back to this project (hopefully in the near future), I'd love to spend a bit more time on this user and make this part of the application more polished. As you can see from my case study, there is quite a lot I would still change and develop, but overall I am very happy with the simplicity and usability of this interface.