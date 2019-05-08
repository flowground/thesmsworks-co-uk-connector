# ![LOGO](logo.png) The SMS Works **flow**ground Connector

## Description

A generated **flow**ground connector for the The SMS Works API (version 1.2.0).

Generated from: https://api.apis.guru/v2/specs/thesmsworks.co.uk/1.2.0/swagger.json<br/>
Generated at: 2019-05-07T17:44:23+03:00

## API Description

The SMS Works provides a low-cost, reliable SMS API for developers. Pay only for delivered texts, all failed messages are refunded.

## Authorization

Supported authorization schemes:
- API Key
## Actions

### Generates an API Key/Secret pair

*Tags:* `auth`

#### Input Parameters
* `customerid` - _required_ - The Customer ID

### x_swagger_router_controller_auth_getApiKey

### Generates a Json Web Token

*Tags:* `auth`

### x_swagger_router_controller_auth_token

### Schedules a batch of SMS messages to be sent at the date time you specify

*Tags:* `batch messages`

### x_swagger_router_controller_batch_schedule

### Send a single SMS message to multiple recipients

*Tags:* `batch messages`

### x_swagger_router_controller_batch_send

### Retrieve all messages in a batch with the given batch ID

*Tags:* `batch messages`

#### Input Parameters
* `batchid` - _required_ - The ID of the batch you would like returned

### x_swagger_router_controller_batch__batchid_

### Cancels a scheduled SMS message

*Tags:* `batch messages`

#### Input Parameters
* `batchid` - _required_ - The ID of the batch you would like returned

### x_swagger_router_controller_batches_schedule__batchid_

### Returns the number of credits currently available on the account

*Tags:* `credits`

### x_swagger_router_controller_credits_balance

### Schedules an SMS message to be sent at the date-time you specify

*Tags:* `messages`

### x_swagger_router_controller_message_schedule

### Sends an SMS message

*Tags:* `messages`

### x_swagger_router_controller_message_send

### Get messages matching your search criteria

*Tags:* `messages`

### x_swagger_router_controller_messages

### Get unread uncoming messages matching your search criteria

*Tags:* `messages`

### x_swagger_router_controller_messages_inbox

### Cancels a scheduled SMS message

*Tags:* `messages`

#### Input Parameters
* `messageid` - _required_ - The ID of the message you would like returned

### x_swagger_router_controller_messages_schedule__messageid_

### Retrieve a logged message by the message ID

*Tags:* `messages`

#### Input Parameters
* `messageid` - _required_ - The ID of the message you would like returned

### x_swagger_router_controller_messages__messageid_

### x_swagger_pipe_swagger

### Returns a sample error object for the given error code. Useful for designing code to react to errors when they occur for real.

*Tags:* `utils`

#### Input Parameters
* `errorcode` - _required_ - The code of the error you would like returned

### x_swagger_router_controller_utils_errors__errorcode_

### Returns the customer ID to the caller

*Tags:* `utils`

### x_swagger_router_controller_utils_test

## License

**flow**ground :- Telekom iPaaS / thesmsworks-co-uk-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
