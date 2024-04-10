---
author: csanders-git
categories:
  - Blog
date: '2018-03-10T20:39:10+01:00'
title: Creating an OpenWAF solution with Nginx, ElasticSearch and ModSecurity [x-post]
---

So many technologies in one title!

Recently I've been spending quite a bit of time investigating [ModSecurity](https://www.modsecurity.org/) as a potential replacement Web Application Firewall, and I've had some really positive results. The purpose of this post is to share with you how I've set this up, so you can do something similar yourself. After all, who wouldn't want to be alerted to suspicious behaviour on their site in slack:
