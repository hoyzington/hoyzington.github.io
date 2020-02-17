---
layout: post
title:      "Sinatra Portfolio Project"
date:       2020-02-17 05:01:21 +0000
permalink:  sinatra_portfolio_project
---


This one was both easier and harder than the CLI project.

It was easier because I now knew better how to build an app, how to use github, and how to use resources to get the info I needed. Also, I had more self-confidence from all that I've experienced so far. And finally, I somehow knew how to let what I was learning beforehand prepare me for the project ahead.

The project was harder because it incorporates so many little things that must be remembered. Rack, db, MVC, routes, erb syntax, and on and on! I'm getting the impression from my cohort leads that I will be very glad to move to Rails, as many of these things are abstracted or brought together in one paradigm instead of this cobbled together approach. But maybe I'm wrong.

My biggest struggle was that I completely forgot about Sinatra nested forms! I think it was because I didn't need any one form to create instances of more than one model. But the problem I encountered--which I hadn't seen or heard about before--was that in my patch route, params includes `_method`, so without assigning all the attributes of my object as the value of a key bearing the object's name, `_method` was being passed to the update method, which did not recognize it.

This bootcamp is the best career decision I've ever made. But I often wonder how much I can retain from learning at this pace. The struggles of these portfolio projects are what helps me to master all this new information.
