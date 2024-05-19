---
title: {{ replace .Name "-" " " | title }}
subtitle: {{ replace .Name "-" " " | title }}
date: {{ .Date }}
draft: false
description: This is the description of the {{ replace .Name "-" " " | title }} post
summary: {{ replace .Name "-" " " | title }}
cover: "images/cover.jpg"
cover_alt: {{ replace .Name "-" " " | title }}
cover_caption: {{ replace .Name "-" " " | title }}
cover_credit: {{ print "© " .Site.Params.authorName ", 2023" }}
categories:
- category1
- category2
tags:
- tag1
- tag2
---
Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet.
