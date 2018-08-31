---
swagger: "2.0"
x-collection-name: Next Caller
x-complete: 0
info:
  title: Next Caller Parameters Version Records
  description: Parameters version records.
  version: 1.0.0
host: api.sandbox.nextcaller.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /{version}/records/:
    parameters:
      summary: Parameters Version Records
      description: Parameters version records.
      operationId: parametersVersionRecords
      x-api-path-slug: versionrecords-parameters
      responses:
        200:
          description: OK
      tags:
      - Version
      - Records
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