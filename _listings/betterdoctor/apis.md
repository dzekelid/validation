---
name: BetterDoctor
description: BetterDoctor helps people find and connect to the best doctors through
  our consumer app, doctor marketing services, and API. Our mission is to help increase
  transparency in healthcare and help consumers make better decisions.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18991-betterdoctor.jpg
x-kinRank: "8"
x-alexaRank: "625342"
tags:
- Technology
- SaaS
- New
- Mobile
- Insurance
- Healthcare
- Doctors
created: "2018-05-13"
modified: "2018-05-13"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/validation/master/_listings/betterdoctor/apis.md
specificationVersion: "0.14"
apis:
- name: BetterDoctor Check if new records exists
  description: 'The endpoint can be used to identify providers with validation data,
    and discover changes. It providers search functionalities like its GET method
    alternative, but does not return any validation data. Instead of the data itself,
    it returns 200 OK if matching validation documents based on the given query are
    found. And it returns 304 if no validation documents are found after the timestamp
    given using If-Modified-Since HTTP header or since parameter. <br><h4 style=''margin-bottom:
    0px !important;''> Return Headers </h4> <div>Last-Modified: Timestamp of the last
    validation made over the matching validations. </div>'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18991-betterdoctor.jpg
  humanURL: https://developer.betterdoctor.com
  baseURL: https://api.betterdoctor.com//2016-03-01
  tags: Validation
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/validation/master/_listings/betterdoctor/validations-head.md
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/validation/master/_listings/betterdoctor/validations-head-postman.md
x-common:
- type: x-blog
  url: https://betterdoctor.com/health/
- type: x-blog-rss
  url: https://betterdoctor.com/health/feed/
- type: x-crunchbase
  url: https://crunchbase.com/organization/betterdoctor-inc
- type: x-developer
  url: https://developer.betterdoctor.com
- type: x-email
  url: hello@betterdoctor.com
- type: x-email
  url: press@betterdoctor.com
- type: x-email
  url: tony@betterdoctor.com
- type: x-email
  url: privacy@betterdoctor.com
- type: x-email
  url: support@betterdoctor.com
- type: x-email
  url: copyright@betterdoctor.com
- type: x-github
  url: https://github.com/betterdoctor
- type: x-twitter
  url: https://twitter.com/betterdoctor
- type: x-website
  url: https://developer.betterdoctor.com
- type: x-website
  url: https://betterdoctor.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---