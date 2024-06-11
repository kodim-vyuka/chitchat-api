# ChitChat API

REST API for the ChitChat training project

## Data model

The data model is for a simple chat application. It continas channels, messages and threads. We provide mock data for some conversations within an imaginary startup company. This company has 9 people:

- Adam - CEO
- Sarah - CTO
- Michael - Lead Developer
- Emily - Frontend Developer
- David - Backend Developer
- Rachel - UX/UI Designer
- Jason - Sales Manager
- Lauren - Customer Success Specialist
- Alex - Marketing Manager

## Running the server

To run the server, run:

```
npx apidroid@latest
```

## Getting the data

`GET /api/channels`

Get all channels

`GET /api/messages?filter=channelId:eq:1`

Get all messages for a channel with id 1

`GET /api/thread-messages?filter=parentId:eq:1`

Get all messages for a thread under the message id 1
