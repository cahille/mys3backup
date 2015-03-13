Want a way to easily backup encrypted, tarballed versions of my svn and cvs repositories over to amazon's s3 service.

Going to have three main functions:

1.  From cron, back up a directory tree and send it to amazon
2.  From cron, verify that the backups in S3 are aok
3.  Be able to restore a backup

