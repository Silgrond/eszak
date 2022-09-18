---
title: "**Image** post"
date: 2018-02-19T12:41:46-05:00
showDate: true
tags: ["blog","story"]
image: "/posts/ideas.png"
draft: true
---

Hello! I'm a blog post with an image. Thanks to Open Graph and Twitter metadata, external links to this page will feature the image below.

![Ideas](/posts/ideas.png)

{{< figure src="/posts/ideas.png" caption="A full-width image with caption." class="full-width" >}}

{{< figure src="/posts/ideas.png" caption="A wide-width image with caption." class="wide-width" >}}

To make this happen, set the `images` parameter in your post's [front-matter](https://gohugo.io/content-management/front-matter/), like this YAML example:

```yaml
images:
    - /posts/ideas.png
```
