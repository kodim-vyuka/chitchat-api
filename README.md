# ChitChat API

REST API for the ChitChat training project

## Running the server

To run the server, run:

```
npx jsonhost@latest
```

## Endpoints

`GET /api/channels`

Get all channels

`GET /api/messages?filter=channelId:eq:1`

Get all messages for a channel with id 1

`GET /api/thread-messages?filter=parentId:eq:1`

Get all messages for a thread under the message id 1


