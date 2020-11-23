---
layout: post
title: About my Side Project
date: 2020-11-22 21:00:01 -0700
categories: side-project
---

I've been working on this project for about two years. I started it over from scratch several times. I hit roadblocks. There were periods of time when I didn't work on it because, for one reason or another, I felt like crap. But in spite of those issues, I managed to work on this project for 159 out of 429 days starting from September 2019, when I started counting, up until November 2020, when I'm writing this post.

I haven't gotten very far into it, but I've learned a lot. Previous versions of the project used Express, Prisma, and a Postgres database. The most recent version uses Dgraph and Apollo GraphQL because I got curious about graph databases and I liked being able to intuitively represent data as a graph in the database itself.

My goal since 2018 has been to code every day. When I started tracking which days I worked on this project, I could only manage to code for about 20 to 40 percent of the days in a given month. Now I've been able to hold steady at about 60 percent of the days in a month. The day I feel fully in control of my life will be the day I hit 100 percent.

# Purpose and Scope

The purpose of this project is to build a platform to create custom forums. If you've used Reddit before - it's like that. Like Reddit, it can be used for both content aggregation (creating feeds with lists of links) and for online discussions.

I chose this project because I care about human-oriented problems with social media.

My plan is to make an app that lets you create a community, submit posts to it and discuss them, and create virtual and in-person events that are searchable sitewide. I want it to be free and open source, and decentralized so that anyone can build an instance of it. And I want it to have strong features for crowdsourced moderation from the beginning. I'm doing this project because I want to implement the ideas I've had to make social media content moderation more effective, more fair, more kind, and more context-specific.

# Stack

The most recent version of my project is a desktop site built with create-react-app. The data is stored in Dgraph, which natively supports GraphQL. The front end is made with React and Node.js, and it communicates with the back end by using Apollo GraphQL. The application state is contained within the Apollo cache.

The plan is to make a React Native mobile app for the same project as well.

# Motivation

We need more creativity and experimentation around building social media platforms in which the business model doesn't depend on ads.

The problem with social media driven by ad revenue is that it incentivizes anything that makes you engage with the app more, even if those types of engagement are not the reason you are using the app in the first place.

The business model driven by ads creates an app that feeds on your attention like a parasite. It encourages endless scrolling, and addictive behaviors of checking feeds over and over again. It also incentivizes people to post and share more emotionally manipulative and divisive posts, because posts that make you feel negative emotions like fear, sadness, and outrage are more likely to cause you to engage with the app by liking, commenting, and sharing posts.

An ad-based business model forces the (usually more boring) truth to compete with (usually more interesting and emotionally manipulative) lies, and when the boring truth competes with lies, it often loses the battle for getting attention on social media platforms.

Then disinformation, misinformation, and conspiracy theories become mainstream, and we find ourselves waking up in a world where millions of people believe things that have been disproven many times. The worst part is that trying to change someone's mind about even one of these false stories is extremely difficult - almost as difficult as getting someone to leave a cult.

I believe that instead of monolithic social media platforms driven by ad revenue, we need a larger constellation of smaller platforms to make it harder for misinformation to rapidly spread across the entire Internet. Smaller platforms shouldn't necessarily lead to a decrease in the quality of the user experience, because you don't need to a billion people to chat with online to have a meaningful experience. You just need a few people who you can relate to, who can also relate to you.

In the way that some people dream about colonizing Mars, I fantasize about a better Internet where people listen to each other more and insult each other less, collaborate more and judge each other less, focus on problem-solving instead of blaming various sets of people for the world's problems, open their minds instead of bickering, post more facts and fewer pictures of text regarding their least favorite politician.

I wish the incentive structure of online communication platforms would change so that people would be recognized for saying the truth instead of controversial or 'edgy' things. I wish consensus was valued more than debate. That's why I believe moderation is important, and the highest priority in my project is to create a fair and transparent moderation system that doesn't rely on admin intervention for the majority of moderation actions.
