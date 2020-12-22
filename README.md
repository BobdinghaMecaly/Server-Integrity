# Server-Integrity
for validation testing  of provisioned servers in an environment
with need the shell script and the ssm doc


for the project,
== the  shell script is placed in a bucket. 
-- a new folder ('log'  -- in this case) for storing the reports. 

and the ssmdoc is an SSM run command document to be used should be edit 

Before executing,
  edit the bucket name where the shell script is 
  the folder name in the s3 where server-reports will be placed
  the shell script name , so that the correct script will be pulled from the bucket. 
  replace the sns topic arn to which notifications will be published.
  ensure the region of the topic is same with bucket etc. 
