---
title: "AWS AppSync VTL Mapping Templates Explained"
date: "2018-06-20T05:11:43.640Z"
layout: post
draft: false
path: "/posts/appsync-vtl-mapping-templates-explained/"
category: "Web Development"
tags:
  - "AWS"
  - "AppSync"
  - "Serverless"
  - "GraphQL"
description: "Demistifying the dark art of AppSync's VTL mapping templates."
---

Recently I've been exploring AWS's new AppSync service. AppSync promises to deliver a scalable, serverless, real-time GraphQL backend as a service. While I have plenty of Node.js experience, I'm new to "serverless" as an architectural paradigm. The stack is somewhat intimidating at first, as there are a lot of potential services you can plug into via lambda and AWS's broad suite of tools.

AppSync abstracts away some of the complexity of pairing GraphQL with serverless technology. It does this with VTL Mapping Templates which map requests and responses between your schema-driven GraphQL endpoint and a DynamoDB instance. Here I will explain the VTL Mapping Template as it applies to AppSync.

## Velocity Templating Language


--

### What Is Velocity?

- Java based template engine
- Can reference methods defined in Java code
- Separates Java code from the web pages themselves, provides an alternative to JSP or PHP
- Can be used to generate web pages, SQL, PostScript or other output from templates
- Can generate source code and reports stand-alone or as a component of another system


### What can Velocity do for You?

- 