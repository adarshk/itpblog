---
layout: post
title: "Mashups Week 1"
description: ""
tags: [Mashups]
comments: true  
share: true
---

###Open API

For open API this week, I initialy decided to use DuckDuckGo's API but after coming across Giphy's open [API](https://github.com/giphy/GiphyAPI) I couldnt resist.The API is well documented and JSON can be retrived with a url similar to this format. 

	http://api.giphy.com/v1/gifs/search?q=funny+cat&api_key=dc6zaTOxFJmzC 

For example a search for the terms 'are+you+serious' returns json with a bunch of gif urls with different formats such as fixed height, fixed width etc.  You can also retrieve gifs by id, tag and trending.By reading their license, it looks like, the number of requests are determined at their discretion but since its in beta they are allowing unrestricted access.

You can also find the html/css source [here](mashups/wk1/index.html)


[//]: To my phone,
[//]: You have always been my home ,
[//]: Never alone,
