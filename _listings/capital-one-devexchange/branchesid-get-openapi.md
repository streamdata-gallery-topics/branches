---
swagger: "2.0"
x-collection-name: Capital One DevExchange
x-complete: 0
info:
  title: Capital One DevExchange Get branch by id
  description: Returns the branch with the specific id
  version: 1.0.0
host: api.reimaginebanking.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /branches:
    get:
      summary: Get all branches
      description: Returns all of the Capital One branches.
      operationId: returns-all-of-the-capital-one-branches
      x-api-path-slug: branches-get
      responses:
        200:
          description: OK
      tags:
      - Banks
      - Branches
  /branches/{id}:
    get:
      summary: Get branch by id
      description: Returns the branch with the specific id
      operationId: returns-the-branch-with-the-specific-id
      x-api-path-slug: branchesid-get
      parameters:
      - in: path
        name: id
        description: ID of branch that needs to be fetched
      responses:
        200:
          description: OK
      tags:
      - Banks
      - Branches
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