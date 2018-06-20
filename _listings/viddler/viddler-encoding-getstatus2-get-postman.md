{
  "info": {
    "name": "Viddler  API Encoding GetStatus2",
    "_postman_id": "a19a35ce-dfce-4e3e-ad7d-d5a17a3ca27b",
    "description": "This method is the same as viddler.encoding.getStatus except that it groups files better for users to easily find what they are looking for. We could not easily update the previous method without causing complications with external applications.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Viddler",
      "item": [
        {
          "id": "1843b525-84cc-481b-9614-f0dbd6f794be",
          "name": "api-echo",
          "request": {
            "url": "http://api.viddler.com/api/v2/viddler.api.echo?message=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "This method is used for testing purposes only. Simply call this method to make sure the API is responding fine."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "64de1960-4a3f-44a0-8275-f80ae9c31de9"
            }
          ]
        },
        {
          "id": "6ced7890-73da-48c9-bdbe-2a13e25b99c7",
          "name": "encoding-cancel",
          "request": {
            "url": "http://api.viddler.com/api/v2/viddler.encoding.cancel?file_id=%7B%7D&sessionid=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Cancel encoding a specific video file."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6cced62b-5488-483d-af8c-795d76f59cbe"
            }
          ]
        },
        {
          "id": "dc04f4c6-53be-4bbf-aa39-5025a8b9efb3",
          "name": "encoding-getsettings",
          "request": {
            "url": "http://api.viddler.com/api/v2/viddler.encoding.getSettings?sessionid=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns the current encoding options for an account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "531db625-e32a-4bff-b258-4d9971292a23"
            }
          ]
        },
        {
          "id": "c8d33e6e-42f3-4a47-afec-afbbbbaa045c",
          "name": "encoding-getstatus2",
          "request": {
            "url": "http://api.viddler.com/api/v2/viddler.encoding.getStatus2?sessionid=%7B%7D&video_id=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "This method is the same as viddler.encoding.getStatus except that it groups files better for users to easily find what they are looking for. We could not easily update the previous method without causing complications with external applications."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "10f6ec38-0cf3-4a96-b903-f2db5f9b274c"
            }
          ]
        }
      ]
    }
  ]
}