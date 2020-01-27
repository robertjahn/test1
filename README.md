**Lab 1 Overview**

In this lab, you will:

1. Connect to your VM

1. Install Dynatrace Agent

1. Start the Demo Application

1. Review Dynatrace

1. Add Tags

1. Add Management Zone

The picture below shows the setup for the lab environment and focus areas for this lab.

Page Break

**Connect to your VM**

The workshop VM instance is provisioned with an SSH web client tool.  Just open your browser to the location provided and login with the credentials provided as shown below:

We will be running many commands as root.  So that the password gets cached, enter this command and enter the same password your used to connect to the VM.  Here is how he prompt looks:

```

dtu\_training@ip-10-0-0-54:~$ sudo ls

 [sudo] password for dtu\_training:

```

**Install Dynatrace OneAgent**

1. To install Dynatrace OneAgent, first login into your Dynatrace tenant. For example: https://\&lt;your tenant\&gt;.sprint.dynatracelabs.com

1. From the left side menu near the bottom, navigate to ```deploy Dynatrace```.  You should see this page



1. Click the &#39;start installation&#39; button and then pick the Linux ption

1. Copy and run the three commands to you VM.

NOTE: For the last one you will need to add sudo. For example:

```

sudo /bin/sh Dynatrace-OneAgent-Linux-1.183.136.sh APP\_LOG\_CONTENT\_ACCESS=1 INFRA\_ONLY=0

```



**Lab 2 Checklist**

In this lab, you should have completed the following:

:white\_check\_mark: How to add x-dynatrace-test HTTP headers and see how they can be combined with Request Attributes rules

:white\_check\_mark: How to use Request Attributes rules during analysis

:white\_check\_mark: How to add Request Naming rules and see how they help during analysis
