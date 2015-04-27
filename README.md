# hadoop-install-shells-script
Install hadoop 2.6 in ubuntu 14.04 using shell script in one go

Using this script you can install and configure hadoop single node cluster only. 
once your script is finished.
# Format your name node
 For the first time, you need to format your namenode, use below command.
  <code>$hdfs namenode -format</code>
  
# Start hadoop using start-all.sh 
 start all file is in sbin of hadoop directory.  <code>$cd hadoop/sbin</code>
  
  <code>$./start-all.sh</code>