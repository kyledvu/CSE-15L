# Week 6 Lab Report (streamlining SSH configuration)

The config file essentially contains information which will be used when logging in to certain servers (similar to how a site can remember your password).
![config](./cse15l-lab-report-images/config-file.png)

To create mine, I simply used notepad. On Windows, in order to create a file without a file extension (such as .txt for example), you can put quotation marks around the name of your file. In this case, my file was named "config".

Now, I can use the Host instead of typing in my full User and HostName when using `ssh`. Doing so looks like this:
![ssh-login](./cse15l-lab-report-images/ieng6-login.png)

Other commands related to `ssh` such as `scp` can also use Host as a replacement for typing out the full User and Hostname.
![scp-text](./cse15l-lab-report-images/scp-text.png)