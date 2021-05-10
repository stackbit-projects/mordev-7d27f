---
title: Projects
hide_title: true
excerpt: projects
sections:
  - title: Specr
    section_id: specr
    image_alt: lorem-ipsum
    content: >
      ## Specr


      A market analysis tool for ecommerce brands. I used Scrapy as a data
      collection tool, and Django as a CMS for the web scraper (selectors,
      websites, start urls), but also as a CMS for the frontend features.


      I initially deployed the web scraper to run via Celery but ran into issues
      with the Twisted Reactor, so I repackaged the scraper so it could be
      deployed to it's own container via scrapyd.


      The project is configured to be deployed to Azure Container Instances
      (deployment yaml included), but there's also a production ready Docker
      Compose image.
    actions: []
    type: section_content
seo:
  title: ''
  description: ''
  robots: []
  extra: []
  type: stackbit_page_meta
layout: advanced
---
