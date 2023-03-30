# Wi-Not-Stop Website

### All Files are statically updated

#deploy

1. npm install
2. gulp clean
3. gulp build
4. install aws cli(and add key) to easily push to s3 bucket
5. DEVELOP: aws s3 sync dist/ s3://wineenergy.wineenergyportal.com --acl public-read
PRODUCTION: aws s3 sync dist/ s3://www.wineenergyva.com --acl public-read
