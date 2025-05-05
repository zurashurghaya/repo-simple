# **Git-Endevor mapping**
### Overview 

This repository was initialized using [Endevor Bridge for Git](https://techdocs.broadcom.com/us/en/ca-mainframe-software/devops/endevor-bridge-for-git/2-0.html).

To know more about Endevor Bridge for Git and how to use it, check the page [Use the Endevor Bridge for Git](https://techdocs.broadcom.com/us/en/ca-mainframe-software/devops/endevor-bridge-for-git/2-0/using.html).

### Install Pre-push hook locally

If you do not have the server pre-receive hook enabled, you need to use the local pre-push hook. You can install the hook in one of two ways:

1. Run the script [scripts/setup.sh](scripts/setup.sh).
<br/>OR
2. Copy manually the [pre-push](scripts/resources/pre-push) script into the hidden `.git/hooks` folder. 
