## serverless-echobot

Echobot for serverless deployment

## Requirements

* NodeJS 12+
* Serverless
* AWS IAM
* Telegram (BotFather)

## Setup

Install [serverless](http://serverless.com/):

```bash
npm install -g serverless
```

Install deps:

```bash
make install
```

## Deploy

```bash
make deploy
```

And set webhook

```bash
make set-webhook BOT_TOKEN=<token> URL=<webhook_endpoint>
```
