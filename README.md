Business History アプリ環境構築 Serverless

1. 01-cognito
   Cognitoサービス構築
2. 02-dynamodb
   Dynamodb構築
  (LocalDB環境については未整備)

3.コンパイル

  serverless deploy -v (dev)
  
  serverless deploy --stage poc
  
  serverless deploy --stage prod
  
  serverless deploy -f function lambdaname

