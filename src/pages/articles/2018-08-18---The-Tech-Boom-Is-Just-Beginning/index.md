---
title: "The Tech Boom Is Just Beginning"
date: "2018-08-18T05:48:35.741Z"
layout: post
draft: false
path: "/posts/the-tech-boom-is-just-beginning/"
category: "Technology"
tags:
  - "AI"
  - "Serverless"
  - "Blockchain"
  - "Cryptoeconomics"
  - "VR"
  - "IOT"
  - "Quantum Computing"
  - "Robotics"
description: "After several decades of explosive growth in technology, we are poised for an even bigger boom."
---

For as long as I can remember, the overriding narrative of the tech industry has been one of never-ending, exponential growth. My earliest memories of computing was interacting with an Apple IIe in my kindergarten classroom in the early 90s. As I grew up, tech grew up with me. We would get our first home computer a few years later, a used Packard Bell 486. This machine was my first gateway to the internet, and I'd use it to dial into AOL. I watched as Windows 3.x got supplanted by Windows 95 and as cable internet superceded dial up. I watched as laptops proliferated college campuses, with free WiFi available in cafes, libraries, and book stores everywhere. I joined in on the social media revolution as people began to intertwine their personal and online lives. The smart phone revolution kicked off by the original iPhone set this trend into hyperspeed.

While it has been incredible watching this tech revolution take place, and I cannot deny its profound impact on my life, I have often wondered when we'll reach "peak tech". After all, the growth we've experienced over the past few decades can't continue forever, right? There's got to be some leveling off. While it would perhaps be nice for society to get a breather and take time to grapple with the implications of tech's recent advances...it's not likely that we'll get any such break any time soon. 

Although mobile computing has reached high levels of saturation, with growth leveling off for Apple's iPhone and Google's Android, some of tech's biggest recent advances are poised to dominate the narrative over the next decade. Unlike past tech revolutions, which happened somewhat sequentially, with the mass market going from desktop computing to portables to internet to mobile...the next decade of tech will see several profoundly different developments occur in parallel.

In other words, it's my prediction that the 2020's will be just as "roaring" as the 1920's, with a decade of explosive economic growth driven by 

- These platforms will eventually exceed the hype
- A brief summary of each and some of the most interesting developments in each one along with predictions of where they will go
- AI
  - Open AI
  - RPA
  - Implications
    - Automation of business processes
    - 
- Robotics
  - Boston Dynamics
  - Warehouse bots
  - Implications
    - Automation of all repeatable processes
- Blockchain
  - Ethereum / Consensys
  - Lightning Labs
  - Coinbase
  - Implications
    - Decentralized organizations
    - We may learn to incentivize societal behavior, distribute workloads
- VR
  - Magic Leap
  - Microsoft
  - Oculus
  - Implications
    - Largely entertainment in the short term
    - Longer term, communication, social networking
- Quantum
  - ???
- IOT
  - ???
  - Implications
    - Track goods
    - Triggers and tracking
    - Industrial automation
- Serverless
  - Lambda
  - Managed services
  - Implications
    - Software development will get faster
    - "One-person unicorn"
- Electric & Solar

# Serverless

## Summary

Going "serverless" means building your applications on top of managed services that charge per execution (rather than per hour) and auto-scale with demand. Gone will be the need to manage Virtual Machines or even Containers. They'll be replaced by Functions uploaded directly to the cloud, scaled and managed by cloud providers such as AWS or Microsoft Azure. The implication for software developers is that we'll be able to achieve more by building on a series of APIs for all "undifferentiated" code and instead focus on the business logic and building delightful user experiences for products.

## Implications

### Real-Time As Default

(rewrite this)
Ever since Google Docs showcased the power of real-time collaboration for document editing, users have begun to demand this capability more and more. Building and scaling a real-time app has been traditionally challenging, however. Although technologies such as websockets have long been part of the web standard it can still be difficult to scale and load balance such a server at scale. Real-time push services such as Google Firebase, Pusher, PubNub, and AWS AppSync promise to make this easy. With the complications abstracted away, real-time will come to be default for all applications.

### Front End Becomes More Important

With some of the meatier problems such as identity management, authorization, real-time syncing, media processing, analytics, streaming, load balancing, server deployment and database management abstracted away behind managed 3rd party services...front end development will become more important than ever. It is on the front-end where the services will connect to produce business value. Managing those services and orchestrating them to produce cohesive and performant user experience will be the exclusive focus of software teams in the future.

### No More Fail Whale

(fact check)
In 2009, Twitter had reached a pivotal moment. The social messaging platform had explosive growth, achieving XX million users in less than YY years. During peak activity, users would sometimes get presented with a cartoon whale indicating the servers were struggling to keep up. And so the infamous "fail whale" was born.  The platform had been built on top of Ruby-on-Rails, a platform that promised simpler development and quicker iteration versus the traditional Java & .NET platforms which were popular at the time.

Serverless apps are poised to get the best of both worlds: quick development cycles and nearly-unlimited scalability.

### Faster Development, Smaller Teams

The proliferation of services will empower smaller teams to achieve more. The teams that learn to leverage the services that exist and combine them in unique ways will gain a huge edge over traditional software teams bogged down by legacy technology. The result is we may see very high quality products produced by small teams. 

(insert quote about one-person unicorn here)

## Examples Today

### Auth0

Auth0 is a managed identity platform as a service. It allows you to ... . Besides being a great platform, it sets a high bar for developer documentation, with rich, clear examples and recipes for nearly every tech stack you can imagine, from PHP to Golang and everything in between. 

### AWS AppSync

AppSync is a relatively new service from AWS that positions itself as a real-time, GraphQL backend as a service. AppSync makes it almost trivial to build a real-time backend for your web or mobile app with its GraphQL Subscriptions support that can scale to millions of users. When used in conjunction with many of the other managed AWS services, such as Cognito, it can be a powerful stack to build on.

### Cloudinary

For managed media services, Cloudinary has emerged as one of the outstanding examples, offering APIs for image & video upload and format conversion, filters, transcripts, trimming, cropping, editing, and more. It's got a straightforward pricing model and automatic CDN support. 

# Blockchain

