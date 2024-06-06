---
name: Youtube
description: >-
  The Youtube API provides the ability to retrieve feeds related to videos,
  users, and playlists. It also provides the ability to manipulate these feeds,
  such as creating new playlists, adding videos as favorites, and sending
  messsages. The API is also able to upload videos.
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
url: https://raw.githubusercontent.com/apis-json/artisanal/main/apis/youtube.yml
created: 2023/10/6
modified: 2023/10/6
specificationVersion: '0.14'
tags: []
apis:
  - name: Youtube Data API
    description: >-
      The YouTube Data API lets you incorporate functions normally executed on
      the YouTube website into your own website or application. The lists below
      identify the different types of resources that you can retrieve using the
      API. The API also supports methods to insert, update, or delete many of
      these resources.
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: https://developers.google.com/youtube/v3
    baseURL: https://www.googleapis.com/youtube/v3
    tags: []
    properties:
      - type: Documentation
        url: https://developers.google.com/youtube/v3/docs
      - type: OpenAPI
        url: properties/youtube-data-openapi-original.yml
    aid: youtube:youtube-data-api
  - name: Youtube Analytics API
    description: >-
      The YouTube Reporting and YouTube Analytics APIs let you retrieve YouTube
      Analytics data to automate complex reporting tasks, build custom
      dashboards, and much more.
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: https://developers.google.com/youtube/analytics
    baseURL: https://api.example.com
    tags: []
    properties:
      - type: Documentation
        url: https://developers.google.com/youtube/analytics/reference
      - type: OpenAPI
        url: properties/youtube-analytics-openapi-original.yml
    aid: youtube:youtube-analytics-api
common:
  - type: Bugs
    url: >-
      https://issuetracker.google.com/issues/new?component=186600&template=874803
  - type: Request Feature
    url: >-
      https://issuetracker.google.com/issues/new?component=186600&template=874803
  - type: Issues
    url: https://issuetracker.google.com/issues?q=componentid:186600
  - type: TermsofService
    url: https://developers.google.com/youtube/terms/api-services-terms-of-service
  - type: Blog
    url: https://blog.youtube/
maintainers:
  - FN: API Evangelist
    url: https://apievangelist.com
    email: info@apievangelist.com
overlays:
  - type: APIs.io Search
    url: overlays/apis-io-search.yml
  - type: API Evangelist Ratings
    url: overlays/apis-io-search.yml
aid: youtube
---