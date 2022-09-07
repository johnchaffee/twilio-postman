# twilio-postman

This repo includes Twilio APIs as downloadable Postman Collections.

## Requirements

- [Twilio Account](https://www.twilio.com/)
- [Postman app](https://www.postman.com/)

## Instructions

1. Download one or more of the [Postman Collections](#postman-collections) below.
2. [Import the collection to Postman](#import-to-postman).
3. Set your [Environment Variables](#set-environment-variables).

## Postman Collections

Click one of the links below to view the Swagger Doc.

| Postman Collection                                                                                                           | Description                                         |
| ---------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------- |
| [Twilio - API](https://github.com/johnchaffee/twilio-postman/blob/main/Twilio%20-%20API.postman_collection.json)                | Send messages and manage accounts and phone numbers |
| [Twilio - Lookups](https://github.com/johnchaffee/twilio-postman/blob/main/Twilio%20-%20API.postman_collection.json)            | Validate Phone Number formats and types             |
| [Twilio - Verify](https://github.com/johnchaffee/twilio-postman/blob/main/Twilio%20-%20API.postman_collection.json)             | Send and validate one-time-passcodes                |
| [Twilio - Messaging Services](https://github.com/johnchaffee/twilio-postman/blob/main/Twilio%20-%20API.postman_collection.json) | Manage Messaging Services and Number Pools          |
| [Twilio - Conversations](https://github.com/johnchaffee/twilio-postman/blob/main/Twilio%20-%20API.postman_collection.json)      | Manage 2-way human-to-human conversations           |

## Import to Postman

Launch Postman and click Import.

![Import button](./images/import-button.png)

Then click the Upload Files button and select one of the Collection files you downloaded in step 1.

![Import dialog](./images/import-dialog.png)

## Set Environment Variables

Select the Environments tab on the left, select an environment such as `Globals`, then create two variables with the following Variable name and Current Value:

| Variable   | Type    | Initial Value | Current Value              |
| ---------- | ------- | ------------- | -------------------------- |
| AccountSid | default |               | \<Your Twilio Account Sid> |
| AuthToken  | secret  |               | \<Your Twilio AuthToken>   |

You can find your Twilio `AccountSid` and `AuthToken` in the [Twilio Console](https://console.twilio.com).

![Environment Variables](./images/env-variables.png)
![Environment Variables](../images/env-variables.png)
![Environment Variables](../../images/env-variables.png)
![Environment Variables](../../../images/env-variables.png)
![Environment Variables](../../images/env-variables.png)
![Environment Variables](../../../images/env-variables.png)
![Environment Variables](../blob/main/images/env-variables.png)
![Environment Variables](../../blob/main/images/env-variables.png)
![Environment Variables](../../../blob/main/images/env-variables.png)