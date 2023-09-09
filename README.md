# infrastructure
Launch EC2.yaml
Windows10:

Create stack
aws cloudformation deploy --template-file C:\Users\Flybear\Desktop\Demofolder\infrastructure_fork\csye6225-infra.yaml --profile dev --region us-east-1 --stack-name static-website --parameter-overrides RegionCode=us-east-1a![image](https://user-images.githubusercontent.com/90993851/198740138-043f4597-1ed0-4c2a-8f40-2c922a3cd599.png)

Delete stack
aws cloudformation delete-stack --stack-name static-website --profile dev![image](https://user-images.githubusercontent.com/90993851/198740172-98ffb1ce-af70-43e8-a607-a6b5316fa9cb.png)


#
