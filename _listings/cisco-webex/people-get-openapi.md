---
swagger: "2.0"
x-collection-name: Cisco WebEx
x-complete: 0
info:
  title: Webex Teams Admin API List people (with exact email)
  description: |-
    List people in your organization.

    https://developer.webex.com/endpoint-people-get.html
  version: 1.0.0
host: api.ciscospark.com
basePath: /v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /people:
    get:
      summary: List people (with exact email)
      description: |-
        List people in your organization.

        https://developer.webex.com/endpoint-people-get.html
      operationId: PeopleGet
      x-api-path-slug: people-get
      parameters:
      - in: query
        name: email
      responses:
        200:
          description: OK
      tags:
      - Video Conferencing
      - List
      - People
      - (with
      - Exact
      - Email)
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---