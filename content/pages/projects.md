---
title: Projects
hide_title: false
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
  - title: 2020 - While working for Ekco
    section_id: lorem-ipsum
    image_alt: lorem-ipsum
    content: >
      ## EKCO - MICROSOFT 365 BACKUP PORTAL


      While working for Ekco I was tasked with rebuilding the Microsoft 365
      backup portal from the ground up. 


      The feature uses the Veeam backup for Microsoft 365 REST API to backup
      Outlook, Onedrive and Sharepoint data to privately hosted backup servers.
      The initial integration had barebones functionality, but was missing out
      on most of the powerful features of the Veeam API.


      I built a python client for communicating with the Veeam API, Flask views
      to allow the user to communicate with the Veeam backend and a nice
      responsive UI using jQuery and bootstrap. 


      <https://www.ek.co/services/protect/office-365-backup>
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
