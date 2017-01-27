# serverless_sms_bot
 A SMS Chatbot built with AWS Lambda, Twilio and Node.
  
## Send a sms text to 720-336-4682 

```sh
Twilio Bot Number: 720-336-4682 
```

##Deploy updates

```sh
$ npm run deploy
```

## facebook chatbot

```sh
$ claudia create --region us-west-1 --api-module bot --configure-fb-bot
$ claudia update --configure-fb-bot
```

## create (first time only)

```sh
$ npm run create
```


## Required tokens

```sh
Twilio Account ID:
```

```sh
Twilio Auth Token:
```

```sh
Twilio Number used for Sending:
```

```sh
AWS IAM user:
```

```sh
aws_access_key_id
```

```sh
aws_secret_access_key
```

```sh
--region us-west-1
```