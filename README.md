# hadoop-install-shells-script
Install hadoop 2.6 in ubuntu 14.04 using shell script in one go

Using this script you can install and configure hadoop single node cluster only. 
once your script is finished.
# Format your name node
  $hdfs namenode -format
  
# Start hadoop using start-all.sh 
 start all file is in sbin of hadoop directory.
  $cd hadoop/sbin
  $./start-all.sh