---
swagger: "2.0"
info:
  title: AWS OpsWorks API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DescribeRdsDbInstances:
    get:
      summary: ' Describe Rds Db Instances '
      description: Describes Amazon RDS instances
      operationId: describeRdsDbInstances
      parameters:
      - in: query
        name: RdsDbInstanceArns
        description: An array containing the ARNs of the instances to be described
        type: string
      - in: query
        name: StackId
        description: The stack ID that the instances are registered with
        type: string
      responses:
        200:
          description: OK
      tags:
      - instances
definitions: []
x-collection-name: AWS OpsWorks
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