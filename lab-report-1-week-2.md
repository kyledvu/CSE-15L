> Lab Activity

This is an image below:

![screenshot for lab](lab_screenshot_demo.PNG)

[Link to main page](https://kyledvu.github.io/cse15l-lab-reports/lab-report-1-week-2.html)

# Remote Access Login Guide
This guide will demonstrate how to log on to the `ieng6` server with your specific UCSD course account.
___
**1. Installing VSCode**

Simply navigate to [this site](https://code.visualstudio.com/) to download VSCode. Make sure that you download the correct version depending on the operating system you have. The home page will look something like this:
![vscode-home-page](vscode-home.png)
___
**2. Remotely Connecting**

 Open up VSCode's terminal (Terminal &#8594; New Terminal in the top left). Then, using the digits associated with your [account information](https://sdacs.ucsd.edu/~icc/index.php), run the following command:
 ```
 $ ssh cs15lwi22zz@ieng6.ucsd.edu
 ```
 Remember to replace the `zz` in the command with your own digits. 
 
 Once you log in, you may be prompted with a few questions, answering yes to all of them is fine. When you have successfully connected, you should see a screen similar to this:
 ![remote-login-screen](remote-login.png)
 ___
 **3. Trying Some Commands**

To make sure everything is working properly, try running some basic commands such as `ls`, `cd ~`, or `pwd`. `ls` will list the files in the current directory, `cd ~` will change the directory to the home directory, and `pwd` will display the path to the current directory. Here are some examples of running these commands below:
![running-example-commands](example-commands.png)