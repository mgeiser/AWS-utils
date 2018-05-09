# AWS-utils
Some basic AWS Utilities


<b>get_s3_bucket_size_monitor.py</b>: This allows you to get size info on S3 buckets for an account.  I have this setup to look for buckets with a total size > 1Tb and list those large bucksts as well as all first level folders.  This example demonstartes using boto3 to get that info from both S3 and Cloudwatch.
<P>I deleted my Access and secret keys.  I may at some point I'll put the Account name, acces san dsecret keys into dict in a List and pass in the List instead of the two explicit calls in the sample.  That would be better software engineering but as-is I got the data needed to manage the S3 bucket size, so it's an MVP...  
  
This little snippette should also run nicely in a Jupyter Notbook; I think it would be well suited for a quick exercise.  I suspect I'll also check in a notebook as well at sime time but not just now. 
  
<P>
