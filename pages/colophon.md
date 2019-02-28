---
title: Colophon
section: colophon
date: 2019-02-07
permalink: /colophon/
---

Web technologies are complex. Designing and building for the fabric of the modern web requires understanding the context you are designing for, which are ever-changing. To build this site, I wanted to choose technologies that were simple, straightfoward, performant, and scalable. Here is a super-nerdy technical rundown.

#### Static Site

Over the past 5 years I've been passionate about static site generators. I remember starting with Jekyll and then I explored other likes Harp, Metalsmith, and many many more. Recently I've played with Gatsby and Hugo. There is much exciting work happening in this space. Recently I came across [Eleventy ("11ty")](https://www.11ty.io/). I needed a fast, bare scaffold for a client project and the [CERN WorldWideWeb re-creation team](https://worldwideweb.cern.ch/) [used it](https://worldwideweb.cern.ch/colophon/) to build their beautiful site. I loved it so much, that I hastily began gutting [a starter template](https://github.com/danurbanowicz/eleventy-netlify-boilerplate) and re-building this site using Eleventy. It is blazing fast, minimal, and offers me everything I need to publish changes, and evolve this space more.

### CMS

Because client-facing work often requires leveraging more robust publishing solutions, I'm acquainted with CMS software. I really love what many in the space are doing. Craft CMS, Statamic, and Kirby have all made incredible inroads at making the CMS development and authoring experience feel human again.

But building and deploying a simple site shouldn't require the complexity of running an entire backend, and managing the complexity of publishing. Thankfully, [Netlify CMS](https://www.netlifycms.org/) is a solution that can be paired with static site tools like Eleventy to create a usable, lightweight publishing view for the site.

This site is wired up to Netlify CMS, where I can quickly author changes securely, that will be versioned in [GitHub](https://github.com) and deployed to the site live.

#### Hosting

[Netlify](https://netlify.com) is a powerful static hosting solution, that has a fast CDN and SSL baked in. Deploying via Git commits is super simple and Netlify even has their own DNS service and secure form endpoints to add dynamic features to a static site. I can't recommend a hosting/deploy pipeline more.

##### Ephemera

For the type on the site, I've used [Rasmus Andersson](https://rsms.me/)'s sublime [Inter typeface family](https://rsms.me/inter/). It is a beautiful neutral typeface, optimized for digital usage.