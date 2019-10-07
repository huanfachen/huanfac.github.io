---
layout: post
---

This post is an introduction to the usage of Anaconda (especially on Windows). It would useful for beginners of Anaconda and Jupyter notebook.

# What is Anaconda

Anaconda is a free and open-source distribution of the Python and R programming languages for data science and scientific computing. It aims to simplify package management and deployment.

Note that Anaconda is not merely for Python programming. You can use it for **R** and **Javascript**.

Also note that anaconda is not the only way to program in Python. You can code and run Python from terminals (such as Linux bash and Windows command line), or from other editors (such as VS Code and PyCharm). Each way has its pros and cons.

# Installation

Remember to install Anaconda with Python 3.7 (or 3.6). Install from [this link](https://docs.anaconda.com/anaconda/install/). 

If Anaconda is installed correctly, you should be able to see these two items *Anaconda Navigator* and *Anaconda Prompt* in the Windows search panel, as follows:

![Snapshot-anaconda-search-res](https://huanfachen.github.io/images/snapshot_anaconda_search_results.png)

# Starting Jupyter notebook

Jupyter notebook is an open-source web application that allows you to create and share documents that containt live code, equations, visualisations and narrative texts. Usually it is used in combination with Anaconda. Usually it is used for .ipynb files.

There are two ways to start a Jupyter notebook. Assume that you have a *hello_world.ipynb* file that is located in the path *C:\\Users\\AnUser\\Documents*. You want to edit this file in Jupyter. 

## Anaconda Navigator
 
The first way is to click and start *Anaconda Navigator*. The navigator provides access to different editors. 

Start Anaconda Navigator from the Windows search box.

![Snapshot-anaconda-nav](https://huanfachen.github.io/images/snapshot_anaconda_navigator.png)

Then choose *Notebook*. You will see a new page opened in your browser. This page is a tree of the file system, the root node being the current user folder. 

You can navigate to the location of the *hello_world.ipynb* file.

But this way is not perfect. First, you can't go outside the root folder of the current user or another disk. Second, it is not very effective. That's why I recommend the other way.

## Anaconda Prompt

Anaconda Prompt is a command prompt that make sure that you are able to use anaconda and conda commands from the prompt.

Start Anaconda Prompt from the Windows search box. Then you see the black box:

![Snapshot-anaconda-prompt](https://huanfachen.github.io/images/snapshot_anaconda_prompt.png)

By default the path is the root folder of the current user. But you are free to navigate to any path or drive, as long as you know basic commands on prompt.

Below is a table of common commands on Windows and Mac/Linux. Please replace <folder-name> and <drive-name> with a specific name.

Purpose | Win command | Mac command
--- | --- | ---
Go to the parent folder | cd .. | cd ..
Go to a folder inside the current folder | cd <folder-name> | cd <folder-name>
Show files and folders | dir | ls
Go to another drive (e.g. d) | d: | cd /media/$USER/<drive-name>

After you navigate to the right folder, type *jupyter notebook*, and a new page on the browser will appear.

For example, I would like to find the *hello_world.ipynb* in the folder of *C:\\Users\\AnUser\\Documents*, so I type the following command:

> cd Documents

And then type *enter*, and then the command:

> jupyter notebook

Type *enter*. The jupyter notebook appears on the browser!

### Know the path

Aonther question is how to find the path of a file or folder? This website will help: https://www.wikihow.com/Find-a-File%27s-Path-on-Windows.

If you are working on UCL Desktop Anywhere, the path to your desktop is: *N:\\DesktopSettings\\Desktop*.

# Basics on command line tools

So what is exactly a prompt (or terminal)?

There are two ways of interacting with a computer, namely a command-line interface (CLI) and a graphical user interface (GUI). Informally, CLI lets you type commands and hit Enter to execute the commands, and GUI lets you 'point and click'. Examples of CLI include Windows command prompt, bash on Linux/Mac. Examples of GUI include Windows GUI and Microsoft Word.

A good CLI has many advantages. If you want to work more efficiently on GIS or data science, I strongly recommend you learn the basics on at least one command line tool. 

If you want to learn Mac/Linux command lines, you will find this website useful:

- [The linux command line](http://linuxcommand.org/tlcl.php)

If you want to learn Windows command prompt, below are some useful websites:

- http://www.cs.columbia.edu/~sedw...
- http://abacus.gene.ucl.ac.uk/sof...
- [Command-Line Reference](https://docs.microsoft.com/en-us/previous-versions/windows/it-pro/windows-server-2008-R2-and-2008/cc754340(v=ws.10)?redirectedfrom=MSDN)
- https://www.sans.org/security-resources/sec560/windows_command_line_sheet_v1.pdf
- [An A-Z Index of the Windows CMD command line](https://ss64.com/nt/)
- [A To Z List Of All Windows CMD Commands - HELLPC.NET](http://www.hellpc.net/2015/08/08/a-to-z-list-of-all-windows-cmd-commands/)
- [148 Windows Run Commands Cheatsheet](https://www.maketecheasier.com/windows-run-commands/)