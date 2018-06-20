---
swagger: "2.0"
x-collection-name: Viddler
x-complete: 0
info:
  title: Viddler  API Api Echo
  description: This method is used for testing purposes only. Simply call this method
    to make sure the API is responding fine.
  termsOfService: http://www.viddler.com/terms-of-use/
  version: v2
host: api.viddler.com
basePath: /api/v2
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  viddler.api.echo:
    get:
      summary: Api Echo
      description: This method is used for testing purposes only. Simply call this
        method to make sure the API is responding fine.
      operationId: api-echo
      x-api-path-slug: viddler-api-echo-get
      parameters:
      - in: query
        name: message
      responses:
        200:
          description: OK
      tags:
      - Viddler
      - Api
      - Echo
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