# AWS-utils
Some basic AWS Utilities


<b>get_s3_bucket_size_monitor.py</b>: This allows you to get size info on S3 buckets for an account.  I have this setup to look for buckets with a total size > 1Tb and list those large bucksts as well as all first level folders.  This example demonstartes using boto3 to get that info from both S3 and Cloudwatch.
<P>I deleted my Access and secret keys.  I may at some point include a .yaml file for the keys bt at this point, not important.  This should also run nicely in a Jupyter Notbook; I think it would be well suited to that.  I suspect I'll also check in a notebook as well. 
  
<P>
