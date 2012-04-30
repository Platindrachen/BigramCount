BigramCount
===========

Compute bigram counts from a collection text files using Hadoop.  
These are steps in learning Hadoop.

To run:  
1. Install Hadoop.   
Download from http://hadoop.apache.org/common/releases.html  
Follow instructions.  
2. Add Hadoop commands to path.  
Edit add_hadoop_to_path.sh, replacing with "ray" with your home directory name.  
From your shell, run this  
    $source add_hadoop_to_path.sh  
3. Compile the Java source to a jar file.  
You need to add the external archive hadoop-x.y.z-core.jar,  
where x.y.z is corresponds to your particular hadoop version number.  
4. Run it.  
input is any directory with a collection of text files.  
The input directory from here contains a dozen usenet text files.  
The output directory will be created during the run.  
    $hadoop jar BigramCount.jar input output  
The input directory from here contains a dozen usenet text files.  
Checkout the output in the output directory.  

TODO: Setup to run on Amazon Elastic Compute Cloud (EC2) servers.

