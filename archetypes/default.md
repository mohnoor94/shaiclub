---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
draft: true
categories: ["أخبار", "مقالات"]
tags: [""]
slug:
hideMeta: true
cover:
    image: images/
    alt: "{{ replace .Name "-" " " | title }}"
    caption: "{{ replace .Name "-" " " | title }}"
---

