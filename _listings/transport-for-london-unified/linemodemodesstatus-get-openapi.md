---
swagger: "2.0"
x-collection-name: Transport for London Unified
x-complete: 0
info:
  title: Transport for London Unified Line  Mode modes  Status
  description: Gets the line status of for all lines for the given modes.
  version: v1
host: api.tfl.gov.uk
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /Journey/Meta/Modes:
    get:
      summary: Journey  Meta  Modes
      description: Gets a list of all of the available journey planner modes.
      operationId: Journey_Meta
      x-api-path-slug: journeymetamodes-get
      responses:
        200:
          description: OK
      tags:
      - Journey
      - ""
      - Meta
      - ""
      - Modes
  /Line/Meta/Modes:
    get:
      summary: Line  Meta  Modes
      description: Gets a list of valid modes.
      operationId: Line_MetaModes
      x-api-path-slug: linemetamodes-get
      responses:
        200:
          description: OK
      tags:
      - Line
      - ""
      - Meta
      - ""
      - Modes
  /Line/Mode/{modes}:
    get:
      summary: Line  Mode modes
      description: Gets lines that serve the given modes..
      operationId: Line_GetByMode
      x-api-path-slug: linemodemodes-get
      parameters:
      - in: path
        name: modes
        description: A comma-separated list of modes e
      responses:
        200:
          description: OK
      tags:
      - Line
      - ""
      - Mode
      - Modes
  /Line/Mode/{modes}/Disruption:
    get:
      summary: Line  Mode modes  Disruption
      description: Get disruptions for all lines of the given modes..
      operationId: Line_DisruptionByMode
      x-api-path-slug: linemodemodesdisruption-get
      parameters:
      - in: path
        name: modes
        description: A comma-separated list of modes e
      responses:
        200:
          description: OK
      tags:
      - Line
      - ""
      - Mode
      - Modes
      - ""
      - Disruption
  /Line/Mode/{modes}/Route:
    get:
      summary: Line  Mode modes  Route
      description: Gets all lines and their valid routes for given modes, including
        the name and id of the originating and terminating stops for each route.
      operationId: Line_RouteByMode
      x-api-path-slug: linemodemodesroute-get
      parameters:
      - in: path
        name: modes
        description: A comma-separated list of modes e
      - in: query
        name: serviceTypes
        description: A comma seperated list of service types to filter on
      responses:
        200:
          description: OK
      tags:
      - Line
      - ""
      - Mode
      - Modes
      - ""
      - Route
  /Line/Mode/{modes}/Status:
    get:
      summary: Line  Mode modes  Status
      description: Gets the line status of for all lines for the given modes.
      operationId: Line_StatusByMode
      x-api-path-slug: linemodemodesstatus-get
      parameters:
      - in: query
        name: detail
        description: Include details of the disruptions that are causing the line
          status including the affected stops and routes
      - in: path
        name: modes
        description: A comma-separated list of modes to filter by
      responses:
        200:
          description: OK
      tags:
      - Line
      - ""
      - Mode
      - Modes
      - ""
      - Status
  /StopPoint/Meta/Modes:
    get:
      summary: Stop Point  Meta  Modes
      description: Gets the list of available stoppoint modes.
      operationId: StopPoint_MetaModes
      x-api-path-slug: stoppointmetamodes-get
      responses:
        200:
          description: OK
      tags:
      - Stop
      - Point
      - ""
      - Meta
      - ""
      - Modes
  /StopPoint/Mode/{modes}:
    get:
      summary: Stop Point  Mode modes
      description: Gets a list of stoppoints filtered by the modes available at that
        stoppoint..
      operationId: StopPoint_GetByMode
      x-api-path-slug: stoppointmodemodes-get
      parameters:
      - in: path
        name: modes
        description: A comma-seperated list of modes e
      - in: query
        name: page
        description: The data set page to return
      responses:
        200:
          description: OK
      tags:
      - Stop
      - Point
      - ""
      - Mode
      - Modes
  /StopPoint/Mode/{modes}/Disruption:
    get:
      summary: Stop Point  Mode modes  Disruption
      description: Gets a distinct list of disrupted stop points for the given modes.
      operationId: StopPoint_DisruptionByMode
      x-api-path-slug: stoppointmodemodesdisruption-get
      parameters:
      - in: query
        name: includeRouteBlockedStops
      - in: path
        name: modes
        description: A comma-seperated list of modes e
      responses:
        200:
          description: OK
      tags:
      - Stop
      - Point
      - ""
      - Mode
      - Modes
      - ""
      - Disruption
  /Mode/ActiveServiceTypes:
    get:
      summary: Mode  Active Service Types
      description: "Returns the service type active for a mode.\r\n            currently
        only supports tube."
      operationId: Mode_GetActiveServiceTypes
      x-api-path-slug: modeactiveservicetypes-get
      responses:
        200:
          description: OK
      tags:
      - Mode
      - ""
      - Active
      - Service
      - Types
  /Mode/{mode}/Arrivals:
    get:
      summary: Mode mode  Arrivals
      description: Gets the next arrival predictions for all stops of a given mode.
      operationId: Mode_Arrivals
      x-api-path-slug: modemodearrivals-get
      parameters:
      - in: query
        name: count
        description: A number of arrivals to return for each stop, -1 to return all
          available
      - in: path
        name: mode
        description: A mode name e
      responses:
        200:
          description: OK
      tags:
      - Mode
      - Mode
      - ""
      - Arrivals
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