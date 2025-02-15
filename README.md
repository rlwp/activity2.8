# activity2.8
ACTIVITY 2.8 ELASTIC BEANSTALK
# my-package

## Build the package
~$ aws elasticbeanstalk create-application-version --rudyl-python-app my-application --version-label v0.0.2 --source-bundle S3Bucket=elasticbeanstalk-us-east-1-255945442255,S3Key=1739593337727-python2.zip

~$ aws elasticbeanstalk create-environment --cname-prefix my-cname --application-name my-app --version-label v1 --environment-name my-env --solution-stack-name "64bit Amazon Linux 2015.03 v2.0.0 running Ruby 2.2 (Passenger Standalone)"
