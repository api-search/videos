---
name: Zoom
description: >-
  This is a starter APIs.json that you can use to learn the specification and
  make your own.
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
url: https://raw.githubusercontent.com/apis-json/artisanal/main/apis/zoom.yml
created: 2023/11/20
modified: 2023/11/20
specificationVersion: '0.16'
tags: []
apis:
  - name: Zoom REST API
    description: >-
      Our REST APIs are organized based on Zoom product, but the base URL for
      all Zoom REST API requests is https://api.zoom.us/v2/ across products.
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: https://developers.zoom.us/docs/api/#rest-apis
    baseURL: https://api.example.com
    tags: []
    properties:
      - type: Documentation
        url: https://developers.zoom.us/docs/api/#rest-apis
      - type: OpenAPI
        url: properties/zoom-openapi-original.yml
    aid: zoom:zoom-rest-api
  - name: Zoom GraphQL API
    description: >-
      Zoom GraphQL is in a public beta. See the GraphQL beta FAQ for details.
      GraphQL is a query language for APIs as well as a runtime environment for
      filling those queries with data.
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: https://developers.zoom.us/docs/api/graphql/overview/
    baseURL: https://api.example.com
    tags: []
    properties:
      - type: Documentation
        url: https://developers.zoom.us/docs/api/graphql/overview/
    overlays: []
    aid: zoom:zoom-graphql-api
common:
  - type: Blog
    url: https://developers.zoom.us/blog/
  - type: Tutorials
    url: https://developers.zoom.us/blog/?tags=tutorial
  - type: Support
    url: https://devsupport.zoom.us/hc/en-us
  - type: Forum
    url: https://devforum.zoom.us/
  - type: Change Log
    url: >-
      https://devsupport.zoom.us/hc/en-us/articles/10007372381325-Developer-Changelog
  - type: GitHub Org
    url: https://github.com/zoom
  - type: Privacy Policy
    url: https://zoom.us/privacy
  - type: Terms of Service
    url: https://explore.zoom.us/docs/en-us/zoom_api_license_and_tou.html
maintainers:
  - FN: API Evangelist
    url: http://apievangelist.com
    email: info@apievangelist.com
overlays:
  - type: APIs.io Search
    url: overlays/apis-io-search.yml
  - type: API Evangelist Ratings
    url: overlays/apis-io-search.yml
aid: zoom
---