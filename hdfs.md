# Ex.No:2. Install, configure, and run Hadoop and HDFS
## Aim
To install, configure, and run Hadoop and HDFS for distributed file system management.

## Procedure
```
1.Install prerequisites, including Java.
2.Download Hadoop and extract the package.
3.Configure environment variables and XML files (core-site.xml, hdfs-site.xml, etc.).
4.Format the NameNode and start the Hadoop services.
5.Test Hadoop by creating directories and uploading files to HDFS.
```
## Steps

1.Install Java:
```
sudo apt update
sudo apt install openjdk-11-jdk -y
java -version
```
2.Configure Hadoop and edit configuration files as explained in the content above.
Start Hadoop services:
```
start-dfs.sh
start-yarn.sh
```
3.Test with commands like:
```
hdfs dfs -mkdir /user
hdfs dfs -put <local_file_path> /user/<username>
```
## Result
Successfully installed, configured, and executed Hadoop with HDFS.


