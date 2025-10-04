---
title: Web Swing Mechanic
layout: page
accent_image: ../../../../images/Portfolio-Background.jpg
---

This project was made in Unreal Engine 5 using C++ for my gameplay mechanics module at university. It is a character controller focused around replicating the iconic web swing of spider man, built around a custom implementation of the physics of the swing and features designed to make it feel as nice as possible for players. Considering how this individual mechanic could be easily slotted into a full game was very interesting, and I enjoyed learning an Unreal Engine way of doing things for this project.

<iframe width="560" height="315" src="https://www.youtube.com/embed/yX-MT0WEeu4?autoplay=1&mute=1">
</iframe>

For full details on any problems mentioned on this page follow this link to see the full devlog on github! [Github: Web Swing Mechanic](https://github.com/dippy2214/Web-Swing-Mechanic/tree/main)
{:.faded}

Throughout this project one of the biggest problems I had to solve was the difference between making lovely realistic physics that do what they would in the real world, and making something that would feel fun for players. This core balance was important, as it still needed to feel like something that was somewhat realistic. The problem is that with realistic physics, it isn't really possible to gain height in the way you would want to when swinging around a city. In fact, you would always slowly lose height (even with perfect execution).

To help this, I made some changes to give players a helping hand with preserving momentum through their swings. The core algorithm is based around Rodrigues' rotation formula, but by the final version I was modifying this to prevent players from losing momentum until after they released their swing. This made the whole motion of the swing feel a lot more fluid, and dramatically improved the feel of the mechanic.

The project was very interesting and engaging, and my one regret with it is that I didn't have more time to put towards it. I had so many ideas for other ways to make it feel even better, like applying a force to push the player away from walls so they didn't scrape along it so much and some sort of grapple option that would pull you towards a specific point for a cool landing, which had to be cut to make sure I could balance this with the other two more intense modules that were running alongside this one in my course. The project was very fun to work on and greatly expanded my skillset, allowing me an opportunity to learn Unreal Engine 5 and have some fun with physics based movement. 