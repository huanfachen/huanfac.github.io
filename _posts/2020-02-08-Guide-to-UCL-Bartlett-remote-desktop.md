---
layout: post
---

This post is an introduction to the use of UCL Bartlett Remote Desktop.

# What is Bartlett Remote Desktop

It is a computer cluster with a GUI on the remote desktop. 

It is for UCL users only, so you need an UCL account and passsword to log on. If you are outside the UCL network environment, you would also need the UCL VPN. Unfortunately, the VPN is sometimes unstable.

Some configurations of the Bartlett Remote Desktop:

- Operating system: MS Windows Server 2012 R2 Datacenter
- Total Physical Memory: 256 GB
- Processors: 2, Intel(R) Xeon(R) CPU E5-2697 @2.70 Hz
- Cores: 24 in total

Note that these resources might be shared among multiple users. In my experience, the major advantage of this cluster is the large RAM, but the computing speed is not very outstanding.

# Start using the Bartlett Remote Desktop

Please follow this link: http://support.bartlett.ucl.ac.uk/category/remote-desktop/

# Sync files on the remote desktop

If you want to upload or sync some files between your local computer and the remote desktop, the UCL N Drive is a good solution. Please follow these steps:

- Add the UCL N Drive to the local machine. Please read this link: https://www.ucl.ac.uk/isd/services/file-storage-sharing/home-n-drive
- Put your files on the N drive. Make them well organised and use meaningful names!
- The files will be quickly added to the N Drive on the remote desktop. In seconds.
- If you update files on one machine, whether the local computer or remote desktop, the files will be synchronised automatically on the N Drive on other machines.

# Installing software on the remote desktop

The UCL ISD said: "Unfortunately, users are unable to install applications within the Desktop Anywhere remote session."

# Installing Anaconda environment on Bartlett Remote Desktop

No you can't.

# Run Python code on the remote desktop

This is what I have done on this remote desktop. The Python installed is 3.7.2. You can add the .py files to N Drive, and run the code on the command line:

> Python path_to_code.py

If you want to use a new package in Python, a workaround is to install the package on another machine (using pip or conda install or others), and then add the "installed folder" to the folder of your .py files on the N Drive.

For example, I want to use the `Pulp` package in Python, so I copy the installed folder of `Pulp` to the N Drive folder containg the `test.py` file. Then I can call the `Pulp` package within the `test.py` file.

# Questions

If you have any question on this Bartlett remote desktop, feel free to ask UCL ISD or drop me an email at `huanfa.chen` at UCL. 

I will reply at the earliest convenience.


