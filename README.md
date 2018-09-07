# SendGridEventsHandlerLambda

## 概要

SendGridのイベントをDynamoDBに記録し、かつ特定のカテゴリ、イベント、属性をSNSに通知するLambda。
DynamoDBへはイベントの全ての内容を記録し、SNSへの通知は環境変数を使って通知内容を取捨選択できるようになっています。

## 参考サイト

以下サイトの情報を参考にしてプログラムを作成しております。

* SendGridのイベントをAPI Gateway -> Lambda(Python) -> DynamoDBに格納する

　　　　https://www.yamamanx.com/sendgrid-api-gateway-lambda-python-dynamodb/

* AWS LambdaからAmazon SNSを介してメールをおくってみる

　　　　http://www.step-forward5.net/entry/2016/08/27/213000

## スターテス

プログラムは現在レビュー中です。
