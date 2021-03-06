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

````bash
sudo apt upgrade
````

You will be asked if you would like to continue... a "y" followed by pressing the return or enter key in any case will suffice.

![](https://github.com/AL0YSI0US/theNuanceGuide/blob/main/img/ubuntu-3-continue.JPG?raw=true)

Neat things are happening.....

![](https://github.com/AL0YSI0US/theNuanceGuide/blob/main/img/ubuntu-4-progress.JPG?raw=true)

You're all set! Do this every few weeks to keep things in your terminal moving efficiently.


## 💼[Linkedin](https://www.linkedin.com/in/a-todd-charliemike/) 

This work by <a xmlns:cc="http://creativecommons.org/ns#" href="https://github.com/AL0YSI0US/" property="cc:attributionName" rel="cc:attributionURL">AL0YSI0US</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>. <a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />

This license lets others distribute, remix, adapt, and build upon your work, even commercially, as long as they credit you for the original creation. This is the most accommodating of licenses offered. Recommended for maximum dissemination and use of licensed materials.
