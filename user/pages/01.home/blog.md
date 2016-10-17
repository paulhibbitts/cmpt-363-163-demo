---
title: Home
blog_url: blog
body_classes: header-image fullwidth
githublink: https://github.com/paulhibbitts/cmpt-363-163-demo/tree/master/user/pages/01.home

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
