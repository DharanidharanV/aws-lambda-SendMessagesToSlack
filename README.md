# aws-lambda-SendMessagesToSlack
This AWS Lambda (Nodejs) code will post the Messages to Slack...

# Nobby Guide
- Log into your Slack account.
- Create a Slack App.
- Enable Incoming Webhooks
- Create an Incoming Webhook
- Use your Incoming Webhook URL to post a message

## Replace Here
```
const options = {
        hostname: "hooks.slack.com",
        method: "POST",
        path: "/services/*********",
      };
```


## To Test run your Lambda

### Sample Payload
```
{
  "name": "yourName",
  "email": "yourEmail",
  "message": "yourMessage...!"
}
```
