# Udacity-DevOps-Promote-Production

-   this will create an S3 bucket and create a cloud front poiting to it
-   with each push
    -   a new S3 bucket will be created
    -   new version of index.html will be copied to it
    -   cloud front will point to the new s3
    -   old S3 will bge deleted ISA.

-   don't forget to delete the final S3 and cloud front instace for the cost :)