---

title: Sticker Machine
date: 2018-10-14 06:42 UTC
subtitle: Level Up Your WeChat Sticker Game
product: A WeChat mini program to discover, share, or save stickers; powered by Giphy.
tags:
  - UX
  - UI
  - Design
  - Wechat
  - Ruby On Rails
previewimage: ../../../../images/projects/stibanner.png
reel: https://www.youtube.com/embed/LnJNU5GrPpQ
---

## WeChat Stickers

are a fun, witty, and cultural treasure trove for everyday social interactions. From private conversations to group banter, it is a badge of coolness and hilarity in the digital community when you produce the perfect sticker at the perfect time.

<iframe width="100%" height="300px" style="margin: 0 auto" src="https://www.youtube.com/embed/LnJNU5GrPpQ" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

## The Opportunity

WeChat users discover stickers through adding them from a conversation where it's posted. When you're browsing other kinds of content like sticker galleries, websites, blogs, or Twitter, it's a challenge to be able to add the gif to your WeChat collection due to its size, format, or cross-app compatibility.

![rec](../images/projects/sticker_4.png)

## Designing Sticker Machine

As WeChat provided the social infrastructure for sharing, I focused on optimizing the visual experience to encourage 'shopping' and sharing stickers at their leisure.

The redesigns between versions 1 & 2 took the margins between stickers away and provided a fuller screen experience.

We decided on 'sticking' the search bar on the bottom (vs. the top) for better access to the human hand holding their mobile device.

![icons](../images/projects/sticker_1.png)
![screens](../images/projects/sticker_2.png)

## Building The Mini Program

The Giphy API was easy to work with, and well-documented. The MVP was up in less than two days-- the challenges that followed were unique to building a product in China (see: Challenges).

## Challenges

Publishing a Mini Program requires the ID of a Chinese citizen-- we worked with a friend to administer and publish our mini program.

The Great Chinese Firewall was the main challenge: publishing content in China requires a business license.

We solved this by re-routing our calls through a middle man server-- our friend's server, which is based in China.

This affected performance-- speed of the load and sticker lag-- which prompted us to cache common searches through Redis.

The language translation feature was later implemented, but could be improved: cross cultural translations and references was something we did not anticipate, but could very well become a worthy mission.

>## Sticker Machine reached upwards of 10,000 visits within the 3-4 days from launch.

## Launch

We hard-launched Sticker Machine at the end of August, 2018 to positive and enthusiastic reception. Sticker Machine reached upwards of 10,000 visits within 3-4 days from launch.

![visits](../images/projects/sticker_3.png)

Generally, people find stickers through WeChat sticker share groups. While that is convenient enough, the stilted, large-group conversation format (300+ people) is inconvenient and not optimal for finding the perfect 'zing' to decorate your wit in an ongoing chat.

## GIPHY

[Giphy](https://www.giphy.com) is a website hosting a database of stickers. Accessing Giphy in China does not require a VPN.

![poweredbygiphy](../images/projects/sticker_5.png)

## Try It!

Scan with your WeChat, or search "Sticker Machine" in WeChat for the mini program.

![stickermachine](../images/projects/sticker_6.png)

## Coverage

<a href="https://mp.weixin.qq.com/s/frnl2ZKI6URYJfF00cuq1g" target="_blank"> How to Use WeChat Like a Local: a Guidebook by Chengdu Expat</a>
<!-- ![poweredbygiphy](../images/projects/) -->
