# Wi-Not-Stop Website

### All Files are statically updated

#deploy

1. npm init
2. gulp clean
3. gulp build
4. install aws cli to easily push to s3 bucket
5. DEVELOP: aws s3 sync dist/ s3://wineenergy.wineenergyportal.com --acl public-read
PRODUCTION: aws s3 sync dist/ s3://www.wineenergyva.com --acl public-read

6. update individual file: aws s3api put-object --bucket wineenergy.wineenergyportal.com --key payonline.html --body dist/payonline.html --acl public-read
