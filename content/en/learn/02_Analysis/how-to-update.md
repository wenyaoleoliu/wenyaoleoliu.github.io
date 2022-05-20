---
title: "How to Update 2"
description: "Regularly update the installed npm packages to keep your Doks website stable, usable, and secure."
lead: "Regularly update the installed npm packages to keep your Doks website stable, usable, and secure."
date: 2020-11-12T13:26:54+01:00
lastmod: 2020-11-12T13:26:54+01:00
draft: false
images: []
type: docs
menu:
  learn:
    parent: "02_analysis"
weight: 610
toc: true
contributors: ["Wenyao Liu"]
cycleofdata: ["Processing", "Analysis", "Sharing"]
programlang: ["R", "Python"]
---

## Problems updating npm packages

Delete the `./node_modules` folder, and run again:

```bash
npm install
```

## Problems with cache

Delete the temporary directories:

```bash
npm run clean
```
