# serverless-artillery

1. Copy .env.example to .env
2. Run `yarn`
3. Run `slsart deploy --stage stress-test`
3. Run `slsart invoke --stage stress-test`
4. See test result here: https://console.aws.amazon.com/lambda/home?region=us-east-1#/functions/serverless-artillery-LMTsGsi-I-stress-test-loadGenerator?tab=monitoring
