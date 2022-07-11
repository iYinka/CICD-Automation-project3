To create CloudFront Distribution:
cd .circleci/files
and run: aws cloudformation deploy \
         --template-file cloudfront.yml \
         --stack-name InitialStack\
         --parameter-overrides WorkflowID=udapeople-iamyinka

where udapeople-iamyinka is the created public s3 Bucket and WorkflowID parameter is now udapeople-iamyinka
