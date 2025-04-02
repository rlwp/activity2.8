# activity2.8
ACTIVITY 2.8 ELASTIC BEANSTALK
# my-package

## Build the package
~$ aws elasticbeanstalk create-application-version --rudyl-python-app my-application --version-label v0.0.2 --source-bundle S3Bucket=elasticbeanstalk-us-east-1-255945442255,S3Key=1739593337727-python2.zip

~$ aws elasticbeanstalk create-environment --cname-prefix my-cname --application-name my-app --version-label v1 --environment-name my-env --solution-stack-name "64bit Amazon Linux 2015.03 v2.0.0 running Ruby 2.2 (Passenger Standalone)"

**1. Prepare the Codebase:**
- Modify your sample codebase as needed. Include all files relevant to the Elastic Beanstallk application.
- Test the modified code locally to ensure it works as expected.

**2. Create the Package Bundle:**
- Use the AWS Elasyic Beanstalk CLI commands to bundle your code. For example:
```
eb init
eb create
eb deploy
```
- Document the exact commands you used and their options in the README file for reference.

**3. Add Files to the Repository:**
- Clone the repository to your local machine using:
```
git clone https://github.com/username/repository.git
```
Replace 'USERNAME' and 'REPOSITORY' with your actual GitHub details.
- Copy your modified codebase and README file into the cloned repository folder.

**4. Commit and Push Files:**
- Add and commit the changes:
```
git add .
git commit -m "Initial commit with modified codebase and README"
```
- Push the changes to the GitHub repository:
```
git push origin main
```

**5. Verify on GitHub:**
- Check your repository online to ensure all files, including the README are uploaded.

