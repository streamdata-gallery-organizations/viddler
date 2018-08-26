---
swagger: "2.0"
x-collection-name: Viddler
x-complete: 0
info:
  title: Viddler  API Encoding GetSettings
  description: Returns the current encoding options for an account.
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
  viddler.encoding.cancel:
    post:
      summary: Encoding Cancel
      description: Cancel encoding a specific video file.
      operationId: encoding-cancel
      x-api-path-slug: viddler-encoding-cancel-post
      parameters:
      - in: query
        name: file_id
      - in: query
        name: sessionid
      responses:
        200:
          description: OK
      tags:
      - Viddler
      - Encoding
      - Cancel
  viddler.encoding.getSettings:
    get:
      summary: Encoding GetSettings
      description: Returns the current encoding options for an account.
      operationId: encoding-getsettings
      x-api-path-slug: viddler-encoding-getsettings-get
      parameters:
      - in: query
        name: sessionid
      responses:
        200:
          description: OK
      tags:
      - Viddler
      - Encoding
      - GetSettings
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