# Flutter AWS-Cognito Sample app

Flutter AWS-Cognito Sample app

## AWS-Cognito

https://docs.aws.amazon.com/ko_kr/cognito/latest/developerguide/what-is-amazon-cognito.html

![cognito](https://docs.aws.amazon.com/ko_kr/cognito/latest/developerguide/images/scenario-cup-cib2.png)

1. In the first step your app user signs in through a user pool and receives user pool tokens after a successful authentication.

2. Next, your app exchanges the user pool tokens for AWS credentials through an identity pool.

3. Finally, your app user can then use those AWS credentials to access other AWS services such as Amazon S3 or DynamoDB.


## User Pool Information

[Jira](https://coazikyeong.atlassian.net/jira/software/projects/CAT/boards/1?selectedIssue=CAT-1)

## Reference

[Medium](https://medium.com/@wesselsbernd/flutter-and-aws-as-of-march-2019-1ad7f40fa9e4)

## Web version

https://origogi.github.io/Flutter_AWS_Cognito_Sample_App/#/

## TODO

- [x] Analyze flutter-cognito plug in
- [x] Implement `Sign up`
- [ ] check to interwork flutter client and AWS-Cognito