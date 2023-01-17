# CSE 15L Week 1 Setup

## Installing Visual Studio Code
1. Go to the VS Code website https://code.visualstudio.com/, and follow the instructions to download and install the specific version for your computer's operating systems.
2. After it is installed, you will be able to open a window that looks similar to this:

![Image](vs_code.png)

## Remotely Connecting
1. For this section, you will learn how to use VS Code/terminal to connect to a remote computer over the Internet to do work there. Situations where you will have to work elsewhere may occur when working on other systems at different institutions or a future job.
2. Install `git` 
3. To use `ssh`, open a terminal in VS Code and put in the command below, replacing the `zz` with the letters in your course-specific account. (Don't include the `$`! It's just a convention for how to write commands.)

`$ ssh cs15lwi23zz@ieng6.ucsd.edu`

4. Because this is your first time connecting to this server, you will receive a message that looks like this:

````
⤇ ssh cs15lwi23zz@ieng6.ucsd.edu
The authenticity of host 'ieng6.ucsd.edu (128.54.70.227)' can't be established.
RSA key fingerprint is SHA256:ksruYwhnYH+sySHnHAtLUHngrPEyZTDl/1x99wUQcec.
Are you sure you want to continue connecting (yes/no/[fingerprint])?
````

5. Type `yes` and press enter. Then, enter your password. The interaction should look like this:

`# On your client

⤇ ssh cs15lwi23zz@ieng6.ucsd.edu

The authenticity of host 'ieng6-202.ucsd.edu (128.54.70.227)' can't be established.

RSA key fingerprint is SHA256:ksruYwhnYH+sySHnHAtLUHngrPEyZTDl/1x99wUQcec.

Are you sure you want to continue connecting (yes/no/[fingerprint])? 

Password: `

`# Now on remote server

Last login: Sun Jan  2 14:03:05 2022 from 107-217-10-235.lightspeed.sndgca.sbcglobal.net
quota: No filesystem specified.

Hello cs15lwi23zz, you are currently logged into ieng6-203.ucsd.edu


You are using 0% CPU on this system


Cluster Status 

Hostname     Time    #Users  Load  Averages  

ieng6-201   23:25:01   0  0.08,  0.17,  0.11

ieng6-202   23:25:01   1  0.09,  0.15,  0.11

ieng6-203   23:25:01   1  0.08,  0.15,  0.11


Sun Jan 02, 2022 11:28pm - Prepping cs15lwi23`

## Testing Commands
