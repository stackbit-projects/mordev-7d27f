---
title: Projects
hide_title: true
excerpt: projects
sections:
  - title: 2021 - side project
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


      <https://github.com/oreilm49/specr>
    actions: []
    type: section_content
  - title: Ekco - Microsoft 365 Backup Portal
    section_id: lorem-ipsum
    image_alt: lorem-ipsum
    content: >
      ## EKCO - MICROSOFT 365 BACKUP PORTAL


      Lorem ipsum dolor sit amet, **consectetur adipiscing elit**, sed do
      eiusmod tempor incididunt ut labore et dolore magna aliqua.


      *   Lorem ipsum

      *   dolor sit amet
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
