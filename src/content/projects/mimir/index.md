---
title: "Mimir"
description: "A tool to reimagine how we use and interact with our own data"
date: "Apr 16 2025"
demoURL: ""
repoURL: ""
---

![Astro Sphere Lighthouse Score](/astro-sphere.jpg)

Mimir is a long term project I've been iterating on for a few years now. The broad goal is to figure out how we can put users data and how they interact with it back in their hands. 

The majority of the world's interactions with technology and each other through that technology are meditated via large private equity backed tech corporations whose interests are often diametrically opposed to their users. 

This has had devastating consequences on both our personal lives and how we interact with each other on a micro level as well as our societies at a macro level. The program is strongly motivated by the work of Cory Doctorow, and is focused on how we can give users control of their own data again and provide a flexible, plugin-based system to build and share their own data gardens that they entirely control.

It draws on a variety of work and research by others:

- ActivityPub
- Webrings
- Ink & Switch
- Raindrop
- Bluesky
- Custom Feeds
- RSS

Currently, I am in the middle of a rewrite from Tauri to Electron. Initially, Tauri felt like the right fit but due to limitations with the library itself as well as the slow pace of development using Rust, I felt it would make more sense to rebuild with Typescript and Electron to get the work done as fast as possible. I have a functioning prototype that I use daily. My aim is to attempt to refine and productionise this when I've released Maliant.
