If running locally, need to also download and run https://github.com/AlexNovitchkovBurbank/sending-messages-nav-component, nav-component, locally.
Note: cannot run locally because goes through api gateway, https://github.com/AlexNovitchkovBurbank/sending-messages-api-gateway, that has authentication via cognito, https://github.com/AlexNovitchkovBurbank/sending-messages-CognitoUserPoolClient. This project was based on jgilberts aws-lambda-stream which I added to publish messages easily to sns and added ses functionality.

CloudFront distribution: https://github.com/AlexNovitchkovBurbank/sending-messages-cloudfront
Cognito user pool and client: https://github.com/AlexNovitchkovBurbank/sending-messages-CognitoUserPool and https://github.com/AlexNovitchkovBurbank/sending-messages-CognitoUserPoolClient
Code deployment bucket, S3: https://github.com/AlexNovitchkovBurbank/sending-messages-code-deployment-bucket
Route53: https://github.com/AlexNovitchkovBurbank/sending-messages-route53
SSL certificate: https://github.com/AlexNovitchkovBurbank/sending-messages-ssl-certificate
SES and the backend: https://github.com/AlexNovitchkovBurbank/Sending-messages-crud-bff

All of which are deployed to AWS
