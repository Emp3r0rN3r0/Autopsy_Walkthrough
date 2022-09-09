# Autopsy_Walkthrough


![image](https://user-images.githubusercontent.com/44712215/189423621-a7c32bfe-ed63-447d-b2b4-643ba241814e.png)


The below is a quick CTF challenge that is meant to get the USER better accustomed to the Autopsy Forensics Platform. 

Step 1: Ensure Autopsy is installed from a legitimate source:
https://www.autopsy.com/download/

Step 2: Download the "bin" zip folder

Step 3: Utilize the missing statement below and conquer the CTF 

Step 4: If unable to execute the CTF, download the PDF walkthrough attached and make it happen.

**MISSION**

We intercepted traffic of a criminal network downloading malware onto a victim's computer. We have 
the network signature of the file, but we do not know where exactly this criminal copied the file. 
Based on logs, we know it is one of the files contained in the bin.tar.gz directory.


The flag is Autopsy{filename} where filename is the name of the malware file.

The hash of the downloaded malware is:
6859e1d10d08c1ea91f6e53ba6d601149b08d4efab8f8c2d586f6858ae1773a7 

The end-state goal of this problem is for you, the student, to identify the malicious file that exists 
within the provided directory. Most of the work has been done for us already, so let us explore the 
most effective avenue of approach using the guided discovery learning process. Utilize the PDF walkthrough
if you become stuck.
