---
title: Home
blog_url: blog
body_classes: header-image fullwidth
githublink: https://csil-git1.cs.surrey.sfu.ca/paulh/cmpt-363-163/tree/master/pages/01.home

sitemap:
    changefreq: monthly
    priority: 1.03

modular_content:
    items: '@self.modular'
    order:
        dir: desc

content:
    items: '@self.children'
    order:
        by: date
        dir: desc
    limit: 0
    pagination: true

feed:
    description: Course Hub Description
    limit: 10

---
