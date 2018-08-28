{
  "info": {
    "name": "Pay Run.IO Delete an Employer",
    "_postman_id": "291474e5-1f35-4076-89d9-e7352fbfd854",
    "description": "Delete the specified employer",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Employer",
      "item": [
        {
          "id": "25f6d93c-b9cd-46ab-aa33-f07738c9354f",
          "name": "DeleteEmployer",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.test.payrun.io",
              "path": [
                "Employer/:EmployerId"
              ],
              "variable": [
                {
                  "id": "EmployerId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "header": [
              {
                "key": "Api-Version",
                "value": "{}",
                "description": "The version of the api to target",
                "disabled": false
              },
              {
                "key": "Authorization",
                "value": "{}",
                "description": "The OAuth 1 authorization header",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Delete the specified employer"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a84784a6-5fa0-4bdf-bd25-823f1441ca8f"
            }
          ]
        }
      ]
    }
  ]
}