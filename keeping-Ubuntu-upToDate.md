# Keeping your Ubuntu up to date

> 🔥 The good folx over at Ubuntu reccomend backing up your computer BEFORE you
>
> **Install / Upgrade** Ubuntu Software.

### Check your Version Of Git

````bash
// The command to run:
git --version 

// Desired Result:
git version 2.25.1

````

If you don't see a supported version of Git, you'll need to either upgrade Git or you will need to do a fresh install, as described below.

````bash
sudo apt-get install git
````

## Update your terminal

````bash
sudo apt update
````

🔓 You will be prompted to enter your password in order to continue.

![](https://github.com/AL0YSI0US/theNuanceGuide/blob/main/img/ubuntu-1-version.JPG?raw=true)

All the packages that are available for installation will be displayed.

In order to see the upgrades available to you, type the following into the command line:

````bash
apt list --upgradable
````

![](https://github.com/AL0YSI0US/theNuanceGuide/blob/main/img/ubuntu-2-upgrade.JPG?raw=true)

You will be asked if you would like to continue... a "y" followed by pressing the return or enter key in any case will suffice.

![](https://github.com/AL0YSI0US/theNuanceGuide/blob/main/img/ubuntu-3-continue.JPG?raw=true)

Neat things happening.....

![](https://github.com/AL0YSI0US/theNuanceGuide/blob/main/img/ubuntu-4-progress.JPG?raw=true)

You're all set! Do this every few weeks to keep things in your terminal moving efficiently.


