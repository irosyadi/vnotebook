---
layout: default
author: irosyadi
title:  Experimental Markdown
date: 2020-11-26 21:10:40
category: development
tags: ["markdown"]
draft: false
---

#  Experimental Markdown

Experimental markdown to check Markdown parser compatibility between VNote+Viki, Gatsby-starter-bee, and Gitbook.


## Comment
`<!-- Write your comments here -->`

Here is the comment:  
<!-- Write your comments here -->

## Symbol List

💬 speech  
🌏️ globe  
⭐️ star  
🚀 rocket  
👣 footprints  
⚓️ anchor  
🔥 fire  
🎯 target  
📌 pin  
⛔ stop  
‼️ double warning  
❗️ warning
⁉️ question  
✔️☑️ check mark  
❌ cross  
ℹ️ info  
📧 email  
🌐 web  
▶▷ triangle  
⚠️ warning  
💥 danger  
📝 note  
☝️ remember  
⚡️ flash

## Iframe
```
<iframe src="https://wttr.in" frameborder="0" width="480" height="299" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>
```

<iframe src="https://wttr.in" frameborder="0" width="480" height="299" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>

## Internal Reference

Content of the up folder (`[Blog Markdown](../development/blog-markdown.md)`)
- [Blog Markdown](../development/blog-markdown.md) : working on jekyll-rtd, gitbook, fail on gatsby
- [Blog](../blog/readme.md) : working on jekyll-rtd, fail on gitbook, fail on gatsby

Content of the up folder (`[Hello](../development/blog-markdown)`)
- [Hello](../development/blog-markdown)  : working on jekyll-rtd, fail on gitbook, fail on gatsby
- [Blog](../blog/readme) : fail on jekyll-rtd, fail gitbook, fail on gatsby

Content of the up folder (`[Hello](../development/blog-markdown/)`)
- [Hello](../development/blog-markdown/) : working on jekyll-rtd, fail on gitbook, fail on gatsby
- [Blog](../blog/readme/) : fail on jekyll-rtd, fail on gitbook, fail on gatsby

- Gatsby understands only link under its folder

## Image Hosting in Github
![QR Code Image-small](_v_images/20201220183102525_18817.png)
![Test QR Code](file:///C:/Users/imron/Pictures/foto%20imron/imron-qr/QR%20Code%20Image-small.png)