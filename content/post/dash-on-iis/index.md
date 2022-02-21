---
title: 'How to deploy dash apps on IIS server'
subtitle: 'A step-by-step guide for windows users'
#summary: Create a beautifully simple website in under 10 minutes.
authors:
- admin
tags:
- dash
- plotly
- python
- data visulisation
categories: [data visualisation]
date: "2022-02-20T00:00:00Z"
#lastmod: "2019-04-17T00:00:00Z"
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal point options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
image:
  caption: ''
  focal_point: "Center"
  preview_only: False

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []

# Set captions for image gallery.
gallery_item:


---

**Dash is an Open Source Python library for creating reactive, Web-based applications.**


While Dash apps are viewed in the web browser, you don’t have to write any Javascript or HTML. Written on top of **Plotly.js** and **React.js**, Dash is ideal for building and deploying data apps with customized user interfaces. It's particularly suited for anyone who works with data. Through a couple of simple patterns, Dash abstracts away all of the technologies and protocols that are required to build a full-stack web app with interactive data visualization.

Not only for reporting purposes, but also when you want to publish a dashboard for your AI models or you want to have an interactive data analysis project, you can employ dash plotly. For becoming more familiar with the power of dash apps you may [**look at the gallery and templates.**](https://dash.gallery/Portal/)

After developing your dashboard using Dash/plotly framework, you have to publish your code on a server, so that users can open and inetarct with your dash app. Usually python apps are better served on an apache server, but it may happen in some cases that you need to deploy your code on a windows server. Specially if your organization is using Microsoft based technologies, you have no other choice than deploying your code on an IIS server. This happend to me at CLdN Cobelfret, and as I couldn't find a step-by-step guide to do the job, I decided to write a post and share my knowledge with others.

you can [follow this link and **read the full article on Medium.**](https://medium.com/@b-nouri/how-to-deploy-your-dash-app-on-iis-windows-server-98a16b8707e1)