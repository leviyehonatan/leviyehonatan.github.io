---
layout: post
title: Running Concurrently
description: "Who did that first? Who?!"
headline: "Let's Fire up the Engines"
categories: coding
tags: [android,ios,multithreading,java]
comments: true
mathjax: null
featured: true
published: true
---

# Motivation
Creating a client application requires a protocol with the server, such as logging in, to supply the identity of the client and to authorise its identity so it can receive data customised to it, for example and not needing to resend that data in subsequence calls. While the HTTP perfectly allows that mainly through the usage of cookies or other type of sessions like query parameters and such, we still need a way to control the order of requests to the server.

