## Infrastructure Architecture

This Application is hosted on AWS. It uses 1 Elastic Beanstalk for the Backend API, 2 S3 Buckets, 1 for the frontend and another 1 for storage uploaded images, and 1 RDS database running Postgres, to save the data.

![Image](screenshots/aws_diagram.png)

## Screenshots:

  AWS RDS - DB:

  ![Image](screenshots/rds.png)
  ![Image](screenshots/rds2.png)
>

  AWS Elastic Beanstalk - BE:

  ![Image](screenshots/beanstalk1.png)
  ![Image](screenshots/beanstalk_env.png)
>

  Buckets preview on dashboard

  ![Image](screenshots/s3-buckets.png)
>

  AWS S3 - FE

  ![Image](screenshots/fe_s3.png)
>

  AWS S3 - Storage Uploaded Images

  ![Image](screenshots/s3_img_bucket.png)
>
