---
swagger: "2.0"
x-collection-name: Predix
x-complete: 0
info:
  title: Predix Analytics Runtime Execute the specified orchestration in asynchronous
    mode.
  version: 1.0.0
  description: To successfully execute the orchestration, the OrchestrationExecutionRequest
    must contain valid orchestration id, asset id, asset data field mapping details.
host: predix-acs.run.aws-usw02-pr.ice.predix.io
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/v2/execution/async:
    post:
      summary: Execute the specified orchestration in asynchronous mode.
      description: To successfully execute the orchestration, the OrchestrationExecutionRequest
        must contain valid orchestration id, asset id, asset data field mapping details.
      operationId: runAsync
      x-api-path-slug: apiv2executionasync-post
      parameters:
      - in: body
        name: body
        description: orchestration execution request
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: Successful response
      tags:
      - Execute
      - Specified
      - Orchestration
      - In
      - Asynchronous
      - Mode
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