{
  "info": {
    "name": "Pay Run.IO Gets the employer",
    "_postman_id": "f8185d76-40dc-4e9e-bde5-cb292e454ed9",
    "description": "Get the specified employer object",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Employer",
      "item": [
        {
          "id": "df2bc4ea-919e-4475-a1c6-418a3908fbf7",
          "name": "GetEmployer",
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
            "method": "GET",
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
            "description": "Get the specified employer object"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9460e7fc-6f9c-4108-8e75-0af7bee110ef"
            }
          ]
        },
        {
          "id": "74115209-a045-4fa9-bd04-e0c6538264bc",
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
              "id": "509dfec7-bbbd-4d7b-9906-531f5ae767f6"
            }
          ]
        }
      ]
    }
  ]
}