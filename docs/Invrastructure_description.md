
# Infrastructure description

<br />

## 1. Architecture Diagram
![Architecture](https://raw.githubusercontent.com/chuonglejp/fullstack-javascript-final-project/master/screenshots/architecture.jpg)

## 2. Amazon RDS For Postgress Database
This app uses Amazon RDS for Postgress databasse hosting, the database endpoint is `psql.c7s2sgwbxgev.ap-southeast-2.rds.amazonaws.com`.

![Amazon RDS](https://raw.githubusercontent.com/chuonglejp/fullstack-javascript-final-project/master/screenshots/rds.jpg)

<br />
<br />

## 3. Amazon Beanstalk For API Hosting
This app uses beanstalk for api hosting, it uses environment named `udagram-api-dev`  and the  application  name is `udagram-api`.
URL: http://udagram-api-dev.ap-northeast-1.elasticbeanstalk.com/

![Beanstalk](https://raw.githubusercontent.com/chuonglejp/fullstack-javascript-final-project/master/screenshots/eb.jpg)

<br />
<br />

## 4. Amazon S3 For Static Front End Web Hosting
This app uses amazon s3 for static front end web hosting, it uses bucket named `udagramchuongle`.
URL: http://udagramchuongle.s3-website-ap-northeast-1.amazonaws.com

![Amazon S3](https://raw.githubusercontent.com/chuonglejp/fullstack-javascript-final-project/master/screenshots/s3.jpg)