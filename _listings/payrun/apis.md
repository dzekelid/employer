---
name: PayRun
x-slug: payrun
description: An open, scalable, transparent and HMRC accredited payroll API. Put the
  power of payroll into your application today.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
x-kinRank: "7"
x-alexaRank: "0"
tags: Employer
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/employer/master/_listings/payrun/apis.md
specificationVersion: "0.14"
apis:
- name: Pay Run.IO - Delete an Employer
  x-api-slug: employeremployerid-delete
  description: Delete the specified employer
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/employer/master/_listings/payrun/employeremployerid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/employer/master/_listings/payrun/employeremployerid-delete-openapi.md
- name: Pay Run.IO - Gets the employer
  x-api-slug: employeremployerid-get
  description: Get the specified employer object
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/employer/master/_listings/payrun/employeremployerid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/employer/master/_listings/payrun/employeremployerid-get-openapi.md
- name: Pay Run.IO - Patches the employer
  x-api-slug: employeremployerid-patch
  description: Patches the specified employer with the supplied values
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/employer/master/_listings/payrun/employeremployerid-patch-openapi.md
- name: Pay Run.IO - Updates the Employer
  x-api-slug: employeremployerid-put
  description: Updates the existing specified employer object
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/employer/master/_listings/payrun/employeremployerid-put-openapi.md
- name: Pay Run.IO - Get employee from employer
  x-api-slug: employeremployeridemployeeemployeeid-get
  description: Gets the specified employee from employer by employee code.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/employer/master/_listings/payrun/employeremployeridemployeeemployeeid-get-openapi.md
- name: Pay Run.IO - Get employees from employer.
  x-api-slug: employeremployeridemployees-get
  description: Get links to all employees for the specified employer.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/employer/master/_listings/payrun/employeremployeridemployees-get-openapi.md
- name: Pay Run.IO - Get employees from employer at a given effective date.
  x-api-slug: employeremployeridemployeeseffectivedate-get
  description: Get links to all employees for the employer on specified effective
    date.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/employer/master/_listings/payrun/employeremployeridemployeeseffectivedate-get-openapi.md
- name: Pay Run.IO - Gets the specified pay code from the employer
  x-api-slug: employeremployeridpaycodepaycodeid-get
  description: Returns the specified pay code from the employer
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/employer/master/_listings/payrun/employeremployeridpaycodepaycodeid-get-openapi.md
- name: Pay Run.IO - Gets the pay codes from the employer
  x-api-slug: employeremployeridpaycodes-get
  description: Get links to all the pay codes for the specified employer
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/employer/master/_listings/payrun/employeremployeridpaycodes-get-openapi.md
- name: Pay Run.IO - Gets the specified pay schedule from the employer
  x-api-slug: employeremployeridpayschedulepayscheduleid-get
  description: Returns the specified pay schedule object from employer
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/employer/master/_listings/payrun/employeremployeridpayschedulepayscheduleid-get-openapi.md
- name: Pay Run.IO - Gets the pay schedule from the specified employer
  x-api-slug: employeremployeridpayschedules-get
  description: Get links to all pay schedules for the specified employer
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/employer/master/_listings/payrun/employeremployeridpayschedules-get-openapi.md
- name: Pay Run.IO - Get pension from employer
  x-api-slug: employeremployeridpensionpensionid-get
  description: Gets the specified pension from employer by pension code.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/employer/master/_listings/payrun/employeremployeridpensionpensionid-get-openapi.md
- name: Pay Run.IO - Get pensions from employer.
  x-api-slug: employeremployeridpensions-get
  description: Get links to all pensions for the specified employer.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/employer/master/_listings/payrun/employeremployeridpensions-get-openapi.md
- name: Pay Run.IO - Get pensions from employer at a given effective date.
  x-api-slug: employeremployeridpensionseffectivedate-get
  description: Get links to all pensions for the employer on specified effective date.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/employer/master/_listings/payrun/employeremployeridpensionseffectivedate-get-openapi.md
- name: Pay Run.IO - Gets the specified report line from the employer
  x-api-slug: employeremployeridreportlinereportlineid-get
  description: Returns the specified pay line from employee
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/employer/master/_listings/payrun/employeremployeridreportlinereportlineid-get-openapi.md
- name: Pay Run.IO - Gets the report lines from the specified employer
  x-api-slug: employeremployeridreportlines-get
  description: Get links to all report lines for the specified employee
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/employer/master/_listings/payrun/employeremployeridreportlines-get-openapi.md
- name: Pay Run.IO - Gets the specified reporting instruction from the employer
  x-api-slug: employeremployeridreportinginstructionreportinginstructionid-get
  description: Returns the specified pay instruction from employee
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/employer/master/_listings/payrun/employeremployeridreportinginstructionreportinginstructionid-get-openapi.md
- name: Pay Run.IO - Gets the reporting instructions from the specified employer
  x-api-slug: employeremployeridreportinginstructions-get
  description: Get links to all pay instructions for the specified employee
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/employer/master/_listings/payrun/employeremployeridreportinginstructions-get-openapi.md
- name: Pay Run.IO - Get all RTI transactions for the employer
  x-api-slug: employeremployeridrtitransactions-get
  description: Get links for all RTI transactions for the specified employer
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/employer/master/_listings/payrun/employeremployeridrtitransactions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/employer/master/_listings/payrun/employeremployeridrtitransactions-get-openapi.md
- name: Pay Run.IO - Delete employer tag
  x-api-slug: employeremployeridtagtagid-delete
  description: Deletes a tag from the employer
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/employer/master/_listings/payrun/employeremployeridtagtagid-delete-openapi.md
- name: Pay Run.IO - Get employer tag
  x-api-slug: employeremployeridtagtagid-get
  description: Gets the tag from the employer
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/employer/master/_listings/payrun/employeremployeridtagtagid-get-openapi.md
- name: Pay Run.IO - Insert employer tag
  x-api-slug: employeremployeridtagtagid-put
  description: Inserts a new tag on the employer
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/employer/master/_listings/payrun/employeremployeridtagtagid-put-openapi.md
- name: Pay Run.IO - Get employer revision tag
  x-api-slug: employeremployeridtagtagideffectivedate-get
  description: Gets the tag from the employer revision
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/employer/master/_listings/payrun/employeremployeridtagtagideffectivedate-get-openapi.md
- name: Pay Run.IO - Get all employer tags
  x-api-slug: employeremployeridtags-get
  description: Gets all the tags from the employer
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/employer/master/_listings/payrun/employeremployeridtags-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/employer/master/_listings/payrun/employeremployeridtags-get-openapi.md
- name: Pay Run.IO - Get all employer revision tags
  x-api-slug: employeremployeridtagseffectivedate-get
  description: Gets all the tags from the employer revision
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/employer/master/_listings/payrun/employeremployeridtagseffectivedate-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/employer/master/_listings/payrun/employeremployeridtagseffectivedate-get-openapi.md
- name: Pay Run.IO - Delete an Employer revision matching the specified revision date.
  x-api-slug: employeremployerideffectivedate-delete
  description: Deletes the specified employer revision for the matching revision date
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/employer/master/_listings/payrun/employeremployerideffectivedate-delete-openapi.md
- name: Pay Run.IO - Gets the employer at the specified effective
  x-api-slug: employeremployerideffectivedate-get
  description: Returns the employer's state at the specified effective date.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/employer/master/_listings/payrun/employeremployerideffectivedate-get-openapi.md
- name: Pay Run.IO - Create a new Employer
  x-api-slug: employers-post
  description: Create a new employer object
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/employer/master/_listings/payrun/employers-post-openapi.md
- name: Pay Run.IO - Get all employer tags
  x-api-slug: employerstags-get
  description: Gets all the employer tags
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/employer/master/_listings/payrun/employerstags-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/employer/master/_listings/payrun/employerstags-get-openapi.md
- name: Pay Run.IO - Get the Employer schema
  x-api-slug: schemasemployer-xsd-get
  description: Returns the Employer schema object
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/employer/master/_listings/payrun/schemasemployer-xsd-get-openapi.md
- name: Pay Run.IO - Gets the employer template
  x-api-slug: templatesemployer-get
  description: Return the employer data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/employer/master/_listings/payrun/templatesemployer-get-openapi.md
x-common:
- type: x-website
  url: http://www.payrun.io
- type: x-api-gallery
  url: http://paypal.api.gallery.streamdata.io
- type: x-api-stack
  url: http://payrun.stack.network
- type: x-documentation
  url: https://developer.payrun.io/docs/home/index.html
- type: x-email
  url: support@payrun.io
- type: x-email
  url: info@payrun.io
- type: x-twitter
  url: https://twitter.com/PayRun_io
- type: x-website
  url: http://api.test.payrun.io
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---