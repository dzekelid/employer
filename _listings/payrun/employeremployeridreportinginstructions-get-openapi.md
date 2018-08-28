---
swagger: "2.0"
x-collection-name: PayRun
x-complete: 0
info:
  title: Pay Run.IO Gets the reporting instructions from the specified employer
  description: Get links to all pay instructions for the specified employee
  version: 17.18.6.206
host: api.test.payrun.io
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /Employer/{EmployerId}:
    delete:
      summary: Delete an Employer
      description: Delete the specified employer
      operationId: DeleteEmployer
      x-api-path-slug: employeremployerid-delete
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      - in: path
        name: EmployerId
        description: The employers unique identifier
      responses:
        200:
          description: OK
      tags:
      - Employer
    get:
      summary: Gets the employer
      description: Get the specified employer object
      operationId: GetEmployer
      x-api-path-slug: employeremployerid-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      - in: path
        name: EmployerId
        description: The employers unique identifier
      responses:
        200:
          description: OK
      tags:
      - Employer
    patch:
      summary: Patches the employer
      description: Patches the specified employer with the supplied values
      operationId: PatchEmployer
      x-api-path-slug: employeremployerid-patch
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      - in: body
        name: Employer
        description: The employer object
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: EmployerId
        description: The employers unique identifier
      responses:
        200:
          description: OK
      tags:
      - Patches
      - Employer
    put:
      summary: Updates the Employer
      description: Updates the existing specified employer object
      operationId: PutEmployer
      x-api-path-slug: employeremployerid-put
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      - in: body
        name: Employer
        description: The employer object
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: EmployerId
        description: The employers unique identifier
      responses:
        200:
          description: OK
      tags:
      - Employer
  /Employer/{EmployerId}/Employee/{EmployeeId}:
    get:
      summary: Get employee from employer
      description: Gets the specified employee from employer by employee code.
      operationId: GetEmployeeFromEmployer
      x-api-path-slug: employeremployeridemployeeemployeeid-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      - in: path
        name: EmployeeId
        description: The employees unique identifier
      - in: path
        name: EmployerId
        description: The employers unique identifier
      responses:
        200:
          description: OK
      tags:
      - Employee
      - From
      - Employer
  /Employer/{EmployerId}/Employees:
    get:
      summary: Get employees from employer.
      description: Get links to all employees for the specified employer.
      operationId: GetEmployeesFromEmployer
      x-api-path-slug: employeremployeridemployees-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      - in: path
        name: EmployerId
        description: The employers unique identifier
      responses:
        200:
          description: OK
      tags:
      - Employees
      - From
      - Employer
  /Employer/{EmployerId}/Employees/{EffectiveDate}:
    get:
      summary: Get employees from employer at a given effective date.
      description: Get links to all employees for the employer on specified effective
        date.
      operationId: GetEmployeesByEffectiveDate
      x-api-path-slug: employeremployeridemployeeseffectivedate-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      - in: path
        name: EffectiveDate
        description: The effective date to be applied
      - in: path
        name: EmployerId
        description: The employers unique identifier
      responses:
        200:
          description: OK
      tags:
      - Employees
      - From
      - Employer
      - At
      - Given
      - Effective
      - Date
  /Employer/{EmployerId}/PayCode/{PayCodeId}:
    get:
      summary: Gets the specified pay code from the employer
      description: Returns the specified pay code from the employer
      operationId: GetPayCodeFromEmployer
      x-api-path-slug: employeremployeridpaycodepaycodeid-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      - in: path
        name: EmployerId
        description: The employers unique identifier
      - in: path
        name: PayCodeId
        description: The pay code unique identifier
      responses:
        200:
          description: OK
      tags:
      - Specified
      - Pay
      - Code
      - From
      - Employer
  /Employer/{EmployerId}/PayCodes:
    get:
      summary: Gets the pay codes from the employer
      description: Get links to all the pay codes for the specified employer
      operationId: GetPayCodesFromEmployer
      x-api-path-slug: employeremployeridpaycodes-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      - in: path
        name: EmployerId
        description: The employers unique identifier
      responses:
        200:
          description: OK
      tags:
      - Pay
      - Codes
      - From
      - Employer
  /Employer/{EmployerId}/PaySchedule/{PayScheduleId}:
    get:
      summary: Gets the specified pay schedule from the employer
      description: Returns the specified pay schedule object from employer
      operationId: GetPayScheduleFromEmployer
      x-api-path-slug: employeremployeridpayschedulepayscheduleid-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      - in: path
        name: EmployerId
        description: The employers unique identifier
      - in: path
        name: PayScheduleId
        description: The pay schedules unique identifier
      responses:
        200:
          description: OK
      tags:
      - Specified
      - Pay
      - Schedule
      - From
      - Employer
  /Employer/{EmployerId}/PaySchedules:
    get:
      summary: Gets the pay schedule from the specified employer
      description: Get links to all pay schedules for the specified employer
      operationId: GetPaySchedulesFromEmployer
      x-api-path-slug: employeremployeridpayschedules-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      - in: path
        name: EmployerId
        description: The employers unique identifier
      responses:
        200:
          description: OK
      tags:
      - Pay
      - Schedule
      - From
      - Specified
      - Employer
  /Employer/{EmployerId}/Pension/{PensionId}:
    get:
      summary: Get pension from employer
      description: Gets the specified pension from employer by pension code.
      operationId: GetPensionFromEmployer
      x-api-path-slug: employeremployeridpensionpensionid-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      - in: path
        name: EmployerId
        description: The employers unique identifier
      - in: path
        name: PensionId
        description: The pensions unique identifier
      responses:
        200:
          description: OK
      tags:
      - Pension
      - From
      - Employer
  /Employer/{EmployerId}/Pensions:
    get:
      summary: Get pensions from employer.
      description: Get links to all pensions for the specified employer.
      operationId: GetPensionsFromEmployer
      x-api-path-slug: employeremployeridpensions-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      - in: path
        name: EmployerId
        description: The employers unique identifier
      responses:
        200:
          description: OK
      tags:
      - Pensions
      - From
      - Employer
  /Employer/{EmployerId}/Pensions/{EffectiveDate}:
    get:
      summary: Get pensions from employer at a given effective date.
      description: Get links to all pensions for the employer on specified effective
        date.
      operationId: GetPensionsByEffectiveDate
      x-api-path-slug: employeremployeridpensionseffectivedate-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      - in: path
        name: EffectiveDate
        description: The effective date to be applied
      - in: path
        name: EmployerId
        description: The employers unique identifier
      responses:
        200:
          description: OK
      tags:
      - Pensions
      - From
      - Employer
      - At
      - Given
      - Effective
      - Date
  /Employer/{EmployerId}/ReportLine/{ReportLineId}:
    get:
      summary: Gets the specified report line from the employer
      description: Returns the specified pay line from employee
      operationId: GetReportLineFromEmployer
      x-api-path-slug: employeremployeridreportlinereportlineid-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      - in: path
        name: EmployerId
        description: The employers unique identifier
      - in: path
        name: ReportLineId
        description: The report line unique identifier
      responses:
        200:
          description: OK
      tags:
      - Specified
      - Report
      - Line
      - From
      - Employer
  /Employer/{EmployerId}/ReportLines:
    get:
      summary: Gets the report lines from the specified employer
      description: Get links to all report lines for the specified employee
      operationId: GetReportLinesFromEmployer
      x-api-path-slug: employeremployeridreportlines-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      - in: path
        name: EmployerId
        description: The employers unique identifier
      responses:
        200:
          description: OK
      tags:
      - Report
      - Lines
      - From
      - Specified
      - Employer
  /Employer/{EmployerId}/ReportingInstruction/{ReportingInstructionId}:
    get:
      summary: Gets the specified reporting instruction from the employer
      description: Returns the specified pay instruction from employee
      operationId: GetReportingInstructionFromEmployer
      x-api-path-slug: employeremployeridreportinginstructionreportinginstructionid-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      - in: path
        name: EmployerId
        description: The employers unique identifier
      - in: path
        name: ReportingInstructionId
        description: The reporting instruction unique identifier
      responses:
        200:
          description: OK
      tags:
      - Specified
      - Reporting
      - Instruction
      - From
      - Employer
  /Employer/{EmployerId}/ReportingInstructions:
    get:
      summary: Gets the reporting instructions from the specified employer
      description: Get links to all pay instructions for the specified employee
      operationId: GetReportingInstructionsFromEmployer
      x-api-path-slug: employeremployeridreportinginstructions-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      - in: path
        name: EmployerId
        description: The employers unique identifier
      responses:
        200:
          description: OK
      tags:
      - Reporting
      - Instructions
      - From
      - Specified
      - Employer
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