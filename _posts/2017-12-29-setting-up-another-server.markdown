---
layout: post
title: "Setting up another server"
date:   2017-12-29 8:43:15 -0500
categories: tech servers
---

# Setting up another server!

I decided to get myself another server, this one is the production server. My current intent is to run Gitlab, Plex, and some production virtual containers with LXC. I picked up an E5-1620v2 with 32 GB of RAM and 2x2 TB hard drive storage. It's a beast on a bad day, and a monster on a good day.

I'm currently running Gitlab in an LXC container, mapped to [gitlab.devme.io](gitlab.devme.io), and plex server mapped to [plex.devme.io](plex.devme.io). On the host, I filter for domain names, and route the appropiate container(s).

## Why the E5?

I wanted something with good speed, good RAM, and newer hard drives - the E5 gave me this (*plus it was the only available server at the time*).

I wanted DDoS protection, as it's a production server, and OVH (the provider) gave me this free of charge.

## What's on the roadmap?

I want to mine some Monero, configure some more LXC containers for research/development/malware analysis, and have some fun!
