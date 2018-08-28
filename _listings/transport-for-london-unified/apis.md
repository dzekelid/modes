---
name: Transport for London Unified
x-slug: transport-for-london-unified
description: We are the integrated transport authority responsible for delivering
  Mayor of London Sadiq Khans strategy and commitments on transport. We run the day-to-day
  operation of the Capitals public transport network and manage Londons main roads.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
x-kinRank: "7"
x-alexaRank: "0"
tags: Modes
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/modes/master/_listings/transport-for-london-unified/apis.md
specificationVersion: "0.14"
apis:
- name: Transport for London Unified - Journey  Meta  Modes
  x-api-slug: journeymetamodes-get
  description: Gets a list of all of the available journey planner modes.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/modes/master/_listings/transport-for-london-unified/journeymetamodes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/modes/master/_listings/transport-for-london-unified/journeymetamodes-get-openapi.md
- name: Transport for London Unified - Line  Meta  Modes
  x-api-slug: linemetamodes-get
  description: Gets a list of valid modes.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/modes/master/_listings/transport-for-london-unified/linemetamodes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/modes/master/_listings/transport-for-london-unified/linemetamodes-get-openapi.md
- name: Transport for London Unified - Line  Mode modes
  x-api-slug: linemodemodes-get
  description: Gets lines that serve the given modes..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/modes/master/_listings/transport-for-london-unified/linemodemodes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/modes/master/_listings/transport-for-london-unified/linemodemodes-get-openapi.md
- name: Transport for London Unified - Line  Mode modes  Disruption
  x-api-slug: linemodemodesdisruption-get
  description: Get disruptions for all lines of the given modes..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/modes/master/_listings/transport-for-london-unified/linemodemodesdisruption-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/modes/master/_listings/transport-for-london-unified/linemodemodesdisruption-get-openapi.md
- name: Transport for London Unified - Line  Mode modes  Route
  x-api-slug: linemodemodesroute-get
  description: Gets all lines and their valid routes for given modes, including the
    name and id of the originating and terminating stops for each route.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/modes/master/_listings/transport-for-london-unified/linemodemodesroute-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/modes/master/_listings/transport-for-london-unified/linemodemodesroute-get-openapi.md
- name: Transport for London Unified - Line  Mode modes  Status
  x-api-slug: linemodemodesstatus-get
  description: Gets the line status of for all lines for the given modes.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/modes/master/_listings/transport-for-london-unified/linemodemodesstatus-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/modes/master/_listings/transport-for-london-unified/linemodemodesstatus-get-openapi.md
- name: Transport for London Unified - Stop Point  Meta  Modes
  x-api-slug: stoppointmetamodes-get
  description: Gets the list of available stoppoint modes.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/modes/master/_listings/transport-for-london-unified/stoppointmetamodes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/modes/master/_listings/transport-for-london-unified/stoppointmetamodes-get-openapi.md
- name: Transport for London Unified - Stop Point  Mode modes
  x-api-slug: stoppointmodemodes-get
  description: Gets a list of stoppoints filtered by the modes available at that stoppoint..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/modes/master/_listings/transport-for-london-unified/stoppointmodemodes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/modes/master/_listings/transport-for-london-unified/stoppointmodemodes-get-openapi.md
- name: Transport for London Unified - Stop Point  Mode modes  Disruption
  x-api-slug: stoppointmodemodesdisruption-get
  description: Gets a distinct list of disrupted stop points for the given modes.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/modes/master/_listings/transport-for-london-unified/stoppointmodemodesdisruption-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/modes/master/_listings/transport-for-london-unified/stoppointmodemodesdisruption-get-openapi.md
- name: Transport for London Unified - Line  Mode modes
  x-api-slug: linemodemodes-get
  description: Gets lines that serve the given modes..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/modes/master/_listings/transport-for-london-unified/linemodemodes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/modes/master/_listings/transport-for-london-unified/linemodemodes-get-openapi.md
- name: Transport for London Unified - Line  Mode modes  Disruption
  x-api-slug: linemodemodesdisruption-get
  description: Get disruptions for all lines of the given modes..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/modes/master/_listings/transport-for-london-unified/linemodemodesdisruption-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/modes/master/_listings/transport-for-london-unified/linemodemodesdisruption-get-openapi.md
- name: Transport for London Unified - Line  Mode modes  Route
  x-api-slug: linemodemodesroute-get
  description: Gets all lines and their valid routes for given modes, including the
    name and id of the originating and terminating stops for each route.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/modes/master/_listings/transport-for-london-unified/linemodemodesroute-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/modes/master/_listings/transport-for-london-unified/linemodemodesroute-get-openapi.md
- name: Transport for London Unified - Line  Mode modes  Status
  x-api-slug: linemodemodesstatus-get
  description: Gets the line status of for all lines for the given modes.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/modes/master/_listings/transport-for-london-unified/linemodemodesstatus-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/modes/master/_listings/transport-for-london-unified/linemodemodesstatus-get-openapi.md
- name: Transport for London Unified - Mode  Active Service Types
  x-api-slug: modeactiveservicetypes-get
  description: "Returns the service type active for a mode.\r\n            currently
    only supports tube."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/modes/master/_listings/transport-for-london-unified/modeactiveservicetypes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/modes/master/_listings/transport-for-london-unified/modeactiveservicetypes-get-openapi.md
- name: Transport for London Unified - Mode mode  Arrivals
  x-api-slug: modemodearrivals-get
  description: Gets the next arrival predictions for all stops of a given mode.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/modes/master/_listings/transport-for-london-unified/modemodearrivals-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/modes/master/_listings/transport-for-london-unified/modemodearrivals-get-openapi.md
- name: Transport for London Unified - Stop Point  Mode modes
  x-api-slug: stoppointmodemodes-get
  description: Gets a list of stoppoints filtered by the modes available at that stoppoint..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/modes/master/_listings/transport-for-london-unified/stoppointmodemodes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/modes/master/_listings/transport-for-london-unified/stoppointmodemodes-get-openapi.md
- name: Transport for London Unified - Stop Point  Mode modes  Disruption
  x-api-slug: stoppointmodemodesdisruption-get
  description: Gets a distinct list of disrupted stop points for the given modes.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/modes/master/_listings/transport-for-london-unified/stoppointmodemodesdisruption-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/modes/master/_listings/transport-for-london-unified/stoppointmodemodesdisruption-get-openapi.md
- name: Transport for London Unified - Line  Mode modes
  x-api-slug: linemodemodes-get
  description: Gets lines that serve the given modes..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/modes/master/_listings/transport-for-london-unified/linemodemodes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/modes/master/_listings/transport-for-london-unified/linemodemodes-get-openapi.md
- name: Transport for London Unified - Line  Mode modes  Disruption
  x-api-slug: linemodemodesdisruption-get
  description: Get disruptions for all lines of the given modes..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/modes/master/_listings/transport-for-london-unified/linemodemodesdisruption-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/modes/master/_listings/transport-for-london-unified/linemodemodesdisruption-get-openapi.md
- name: Transport for London Unified - Line  Mode modes  Route
  x-api-slug: linemodemodesroute-get
  description: Gets all lines and their valid routes for given modes, including the
    name and id of the originating and terminating stops for each route.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/modes/master/_listings/transport-for-london-unified/linemodemodesroute-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/modes/master/_listings/transport-for-london-unified/linemodemodesroute-get-openapi.md
- name: Transport for London Unified - Line  Mode modes  Status
  x-api-slug: linemodemodesstatus-get
  description: Gets the line status of for all lines for the given modes.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/modes/master/_listings/transport-for-london-unified/linemodemodesstatus-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/modes/master/_listings/transport-for-london-unified/linemodemodesstatus-get-openapi.md
- name: Transport for London Unified - Mode  Active Service Types
  x-api-slug: modeactiveservicetypes-get
  description: "Returns the service type active for a mode.\r\n            currently
    only supports tube."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/modes/master/_listings/transport-for-london-unified/modeactiveservicetypes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/modes/master/_listings/transport-for-london-unified/modeactiveservicetypes-get-openapi.md
- name: Transport for London Unified - Mode mode  Arrivals
  x-api-slug: modemodearrivals-get
  description: Gets the next arrival predictions for all stops of a given mode.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/modes/master/_listings/transport-for-london-unified/modemodearrivals-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/modes/master/_listings/transport-for-london-unified/modemodearrivals-get-openapi.md
- name: Transport for London Unified - Stop Point  Mode modes
  x-api-slug: stoppointmodemodes-get
  description: Gets a list of stoppoints filtered by the modes available at that stoppoint..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/modes/master/_listings/transport-for-london-unified/stoppointmodemodes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/modes/master/_listings/transport-for-london-unified/stoppointmodemodes-get-openapi.md
- name: Transport for London Unified - Stop Point  Mode modes  Disruption
  x-api-slug: stoppointmodemodesdisruption-get
  description: Gets a distinct list of disrupted stop points for the given modes.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/modes/master/_listings/transport-for-london-unified/stoppointmodemodesdisruption-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/modes/master/_listings/transport-for-london-unified/stoppointmodemodesdisruption-get-openapi.md
- name: Transport for London Unified - Stop Point  Mode modes  Disruption
  x-api-slug: stoppointmodemodesdisruption-get
  description: Gets a distinct list of disrupted stop points for the given modes.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/modes/master/_listings/transport-for-london-unified/stoppointmodemodesdisruption-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/modes/master/_listings/transport-for-london-unified/stoppointmodemodesdisruption-get-openapi.md
- name: Transport for London Unified - Stop Point  Mode modes
  x-api-slug: stoppointmodemodes-get
  description: Gets a list of stoppoints filtered by the modes available at that stoppoint..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/modes/master/_listings/transport-for-london-unified/stoppointmodemodes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/modes/master/_listings/transport-for-london-unified/stoppointmodemodes-get-openapi.md
- name: Transport for London Unified - Mode mode  Arrivals
  x-api-slug: modemodearrivals-get
  description: Gets the next arrival predictions for all stops of a given mode.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/modes/master/_listings/transport-for-london-unified/modemodearrivals-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/modes/master/_listings/transport-for-london-unified/modemodearrivals-get-openapi.md
- name: Transport for London Unified - Mode  Active Service Types
  x-api-slug: modeactiveservicetypes-get
  description: "Returns the service type active for a mode.\r\n            currently
    only supports tube."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/modes/master/_listings/transport-for-london-unified/modeactiveservicetypes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/modes/master/_listings/transport-for-london-unified/modeactiveservicetypes-get-openapi.md
- name: Transport for London Unified - Line  Mode modes  Status
  x-api-slug: linemodemodesstatus-get
  description: Gets the line status of for all lines for the given modes.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/modes/master/_listings/transport-for-london-unified/linemodemodesstatus-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/modes/master/_listings/transport-for-london-unified/linemodemodesstatus-get-openapi.md
- name: Transport for London Unified - Line  Mode modes  Route
  x-api-slug: linemodemodesroute-get
  description: Gets all lines and their valid routes for given modes, including the
    name and id of the originating and terminating stops for each route.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/modes/master/_listings/transport-for-london-unified/linemodemodesroute-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/modes/master/_listings/transport-for-london-unified/linemodemodesroute-get-openapi.md
- name: Transport for London Unified - Line  Mode modes  Disruption
  x-api-slug: linemodemodesdisruption-get
  description: Get disruptions for all lines of the given modes..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/modes/master/_listings/transport-for-london-unified/linemodemodesdisruption-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/modes/master/_listings/transport-for-london-unified/linemodemodesdisruption-get-openapi.md
- name: Transport for London Unified - Line  Mode modes
  x-api-slug: linemodemodes-get
  description: Gets lines that serve the given modes..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/modes/master/_listings/transport-for-london-unified/linemodemodes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/modes/master/_listings/transport-for-london-unified/linemodemodes-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://transitfeeds.api.gallery.streamdata.io
- type: x-api-stack
  url: http://transport.for.london.unified.stack.network
- type: x-developer
  url: http://api.tfl.gov.uk
- type: x-website
  url: https://tfl.gov.uk/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---