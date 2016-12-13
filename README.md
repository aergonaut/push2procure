# Push2Procure

## PREREQUISITES

*   [Serverless](https://serverless.com/) installed on your local machine
*   [AWS IoT Button](https://aws.amazon.com/iotbutton/)
*   Working Coupa instance
*   Coupa API key

## DEPLOY

```
API_HOST=your.host.tld API_KEY=YourApiKey serverless deploy
```

## CONFIG

Connect the Serverless app with your IoT Button in the AWS IoT Dashboard:

1.  Select **Rules** in the sidebar and select your button
2.  Add a new action to your button and select the Lambda type
3.  Choose the Lambda function created by Serverless

## BACKGROUND

Push2Procure was built for an internal hackday event. It may or may not work as
advertised. YMMV.

## LICENSE

All rights reserved.
