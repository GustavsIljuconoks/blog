---
author: kerri
pubDatetime: 2023-09-21T15:22:00Z
title: "Creating a photopgraphy portfolio website"
postSlug: starting-kreics-project
featured: true
draft: false
tags:
  - "Blog"
ogImage: ""
description:
  I started a new project!!
---

I'm very happy to announce that I was offered an oppurtunity to create a photography portfolio website for [kreics.com][kreics-ig]. 

Page content will contain index, about me page, photo gallery and contact form. As this is my first big web project I am very excited to work on it. Of course a lot of things are new for me, and a lot of difficulties are expected. I'm hoping to publish it by the end of this autumn.

As for technologies used in this project - I'm sticking to [React][react], [Tailwind][tailwind] and [Firebase][firebase].

Right now there is noticeable progress. I have created UI and styled it (it's possible that some things will change) and implemented React, created Firebase storage and database with mock data. Firebase application in this project is big, as this will serve as my database and server, but it is a new technology for me, so any complications with it's usage are expected.

When creating storages and databases I came to a conclusion, that it's best for me to create a file content management system for the client. It will be more effective and scalable in the future. This type of system would allow client to upload his desired photo to a Firebase storage and url created for that specific image would be saved in database. This process would happen automatically and would allow for easier content management.

Hope to get this working without getting in too much trouble with Firebase hehe.

Thanks for reading!
See you in the next blog post.


[kreics-ig]: https://www.instagram.com/kreicsfilms/
[react]: https://react.dev/
[tailwind]: https://tailwindcss.com/
[firebase]: https://firebase.google.com/