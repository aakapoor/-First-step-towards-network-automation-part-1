
SDN is buzzword nowadays and there is API to run commands or configure network devices.

But there are still many legacy devices, which require command line interaction.

For those legacy devices you may use this script to run a set of commands on multiple network devices. 

There are multiple ways to achieve this task, I am using expect. 

Best parts of expect script is that it is very easy to understand and work with, it displays every step on terminal, and you may cancel it anytime with “ctrl+c”.

In this example I am connecting to multiple route-servers and running command to check their BGP neighbors and routes they have learnt for particular route. 

Disclaimer: This is for educational purpose only do not use this script on production boxes without proper testing.

Most route-servers restrict running script, please check before running script.

This script use four files

Check below link for more details 

http://www.linkedin.com/pulse/first-step-towards-network-automation-part-1-aashish-kapoor
