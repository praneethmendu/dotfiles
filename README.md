Dotfiles Template
=================

This is a template repository for bootstrapping your dotfiles with [Dotbot][dotbot].

To get started, you can [fork][fork] this repository (and probably delete this
README and rename your version to something like just `dotfiles`).

In general, you should be using symbolic links for everything, and using git
submodules whenever possible.

To keep submodules at their proper versions, you could include something like
`git submodule update --init --recursive` in your `install.conf.yaml`.

To upgrade your submodules to their latest versions, you could periodically run
`git submodule update --init --remote`.

Inspiration
-----------

If you're looking for inspiration for how to structure your dotfiles or what
kinds of things you can include, you could take a look at some repos using
Dotbot.

* [anishathalye's dotfiles][anishathalye_dotfiles]
* [csivanich's dotfiles][csivanich_dotfiles]
* [m45t3r's dotfiles][m45t3r_dotfiles]
* [alexwh's dotfiles][alexwh_dotfiles]
* [azd325's dotfiles][azd325_dotfiles]
* [bluekeys' dotfiles][bluekeys_dotfiles]
* [wazery's dotfiles][wazery_dotfiles]
* [thirtythreeforty's dotfiles][thirtythreeforty_dotfiles]

And there are about [700 more here][dotbot-users].

If you're using Dotbot and you'd like to include a link to your dotfiles here
as an inspiration to others, please submit a pull request.

License
-------

This software is hereby released into the public domain. That means you can do
whatever you want with it without restriction. See `LICENSE.md` for details.

That being said, I would appreciate it if you could maintain a link back to
Dotbot (or this repository) to help other people discover Dotbot.

[dotbot]: https://github.com/anishathalye/dotbot
[fork]: https://github.com/anishathalye/dotfiles_template/fork
[anishathalye_dotfiles]: https://github.com/anishathalye/dotfiles
[csivanich_dotfiles]: https://github.com/csivanich/dotfiles
[m45t3r_dotfiles]: https://github.com/m45t3r/dotfiles
[alexwh_dotfiles]: https://github.com/alexwh/dotfiles
[azd325_dotfiles]: https://github.com/Azd325/dotfiles
[bluekeys_dotfiles]: https://github.com/bluekeys/.dotfiles
[wazery_dotfiles]: https://github.com/wazery/dotfiles
[thirtythreeforty_dotfiles]: https://github.com/thirtythreeforty/dotfiles
[dotbot-users]: https://github.com/anishathalye/dotbot/wiki/List-of-Dotbot-Users









system we also receive the latest updates whenever you check for system updates.

$ wget -q -O - https://dl-ssl.google.com/linux/linux_signing_key.pub | sudo apt-key add -
Now add the PPA url to /etc/apt/sources.list.d/google.list

64-Bit Systems:

$ sudo sh -c 'echo "deb [arch=amd64] http://dl.google.com/linux/chrome/deb/ stable main" >> /etc/apt/sources.list.d/google.list'
32-Bit Systems:

$ sudo sh -c 'echo "deb http://dl.google.com/linux/chrome/deb/ stable main" >> /etc/apt/sources.list.d/google.list'
Step 2: Install or Upgrade Google Chrome

After adding Google chrome repository in our system use following commands to install latest Google chrome stable release. If you already have installed an older version, It will upgrade currently installed version with recent stable version.

$ sudo apt-get update
$ sudo apt-get install google-chrome-stable
Step 3: Start Google Chrome

After completing step 2 the Google chrome has been installed successfully on our system. Let start Google chrome using the desktop menu or using one of the following commands.

 $ google-chrome &
 [or]
 $ google-chrome-stable &
Install or Upgrade Google Chrome

Congratulation’s you have successfully installed Google chrome on Ubuntu system.

We can also use Google chrome GUI installer to install with graphical interface.

 Share
 
 Tweet
 
 Share
 
 Share
 
 Share
 
 Share
 
 

 
Rahul K.
RAHUL K.  
I, Rahul Kumar is the founder and chief editor of TecAdmin.net. I am Red Hat Certified Engineer (RHCE) and working as IT professional since 2009.

  PREVIOUS ARTICLE
How to Install Google Chrome 57 in CentOS/RHEL 7/6 & Fedora 25/24
NEXT ARTICLE  
How to Install JAVA 8 (JDK/JRE 8u121) on Debian 8 & 7 via PPA
RELATED POSTS

How to Install Firefox 53.0 on Linux Systems
August 3, 2016
How to Install Google Chrome 57 in CentOS/RHEL 7/6 & Fedora 25/24
March 25, 2016
What is Gmail IMAP Settings ?
January 17, 2015
24 COMMENTS
NIMROD MILO  REPLY TO NIMROD
April 15, 2017 at 6:36 am
If you have 64bit architecture you need to use: deb [arch=amd64] http://dl.google.com/linux/chrome/deb/ stable main in the file

Suggested in: https://askubuntu.com/questions/743814/unable-to-find-expected-entry-main-binary-i386-packages-chrome

Rahul K.RAHUL K.  REPLY TO RAHUL
April 17, 2017 at 11:25 am
Thanks Milo,

Article has been updated accordingly

TESTOS  REPLY TO TESTOS
June 9, 2016 at 5:26 am
Failed to move to new namespace: PID namespaces supported, Network namespace supported, but failed: errno = Operation not permitted

BUCHANAN  REPLY TO BUCHANAN
April 25, 2016 at 5:09 am
Ditto exactly Andy’s comments above.

ANDY  REPLY TO ANDY
April 11, 2016 at 1:34 pm
Unfortunately I’m getting “W: Failed to fetch http://dl.google.com/linux/chrome/deb/dists/stable/Release Unable to find expected entry ‘main/binary-i386/Packages'” on a fresh install of 14.04 Ubuntu on a 32-bit machine.

JORDAN  REPLY TO JORDAN
June 1, 2016 at 12:49 am
same

JIIVA  REPLY TO JIIVA
April 3, 2016 at 4:55 am
I installed remote desktop in Linux14 bt could not access termial fo install firefor

MANOJ CHAKRABORTY  REPLY TO MANOJ
January 1, 2016 at 3:11 am
How to run chrome as root user in Ubuntu?

BBATTEASE  REPLY TO BBATTEASE
August 16, 2015 at 1:17 am
Thanks so much, this worked perfectly (running Ubuntu 15.04). The unfortunate part is that I ONLY need Chrome for Netlfix!

MYKE MUCHABEE  REPLY TO MYKE
July 21, 2015 at 5:36 am
“Google is evil” is a popular opinion, and you trust Google?

SIZIGIA  REPLY TO SIZIGIA
May 14, 2016 at 5:09 pm
Do you trust in a popular opinion? Poor you. You should learn to use your brain.

SURESH  REPLY TO SURESH
June 6, 2015 at 5:54 pm
After running: “sudo apt-get update” on Ubuntu 14.04 32-bit.the following error is being thrown pls help me in this regard,…………..

W: GPG error: http://in.archive.ubuntu.com trusty-backports Release: The following signatures were invalid: BADSIG 40976EAF437D05B5 Ubuntu Archive Automatic Signing Key
W: Duplicate sources.list entry http://dl.google.com/linux/chrome/deb/ stable/main i386 Packages (/var/lib/apt/lists/dl.google.com_linux_chrome_deb_dists_stable_main_binary-i386_Packages)
W: Duplicate sources.list entry http://dl.google.com/linux/chrome/deb/ stable/main i386 Packages (/var/lib/apt/lists/dl.google.com_linux_chrome_deb_dists_stable_main_binary-i386_Packages)

POLDOWN  REPLY TO POLDOWN
January 30, 2017 at 12:34 pm
try “deb [arch=amd64] https://dl-ssl.google.com/linux/chrome/deb/ stable main” instead

DEWEEZY  REPLY TO DEWEEZY
June 1, 2015 at 8:43 pm
THaaaannnXx TO Bud :* :* it really Help’s Thanks again

SUMMON AGUS  REPLY TO SUMMON
April 27, 2015 at 10:40 am
hello there, i cant update my Google Chrome on Ubuntu 14.04…

CHRISTIAN HARMS  REPLY TO CHRISTIAN
December 14, 2014 at 6:55 pm
Sorry – not every is trusting google …

Second: chrome has a sandbox system for every tab – so it is memory hungry and NOT a light weight browser.

And take a look on a defintion for a ” multi user environment” …..

KETAN  REPLY TO KETAN
October 8, 2014 at 2:13 pm
whoooiiiee.. worked for me..!
Thanks for the help.

ED  REPLY TO ED
September 20, 2014 at 7:07 pm
Or maybe just
sudo echo “deb http://dl.google.com/linux/chrome/deb/ stable main” >> /etc/apt/sources.list.d/google.list
for the second command? I’m not sure why we’re needlessly complicating things by calling a shell from a shell.

PEELUS  REPLY TO PEELUS
October 11, 2014 at 11:25 pm
I tried- got permission error on writing to file.

DIMITRY  REPLY TO DIMITRY
October 21, 2014 at 6:14 pm
Because when you do sudo command >> file.txt you’re doing 2 operatuins: a) executing `command` under sudo permissions b) writing output of that command into file.txt. The problem if you do it simply by `sudo command >> file.txt` than sudo will NOT apply to actual operation of writing to `file.txt` and you will get permisson errror.

AAAA  REPLY TO AAAA
January 7, 2015 at 1:00 pm
echo “deb http://dl.google.com/linux/chrome/deb/ stable main” | sudo tee /etc/apt/sources.list.d/google.list

BUDY  REPLY TO BUDY
August 29, 2014 at 3:40 am
thanks…gonna try it now

A.K  REPLY TO A.K
February 14, 2014 at 4:50 pm
Thanks for the help. Worked perfectly for me. I was able to successfully install chrome once again.

CHRIS  REPLY TO CHRIS
February 11, 2014 at 6:23 am
Noone should trust google chrome.

LEAVE A REPLY

COMMENTS *

NAME * 
EMAIL * 
WEBSITE

SUBMIT 
NOTIFY ME OF FOLLOW-UP COMMENTS BY EMAIL.


 
Search for: 
Search Now
 Search
5366
follow 
893
follow 
734
follow
19
follow 
0
subscribe

 
POPULAR POSTS

upgrade to ubuntu 17
How To Upgrade to Ubuntu 17.04 (Zesty Zapus)
Prevent SQL Injection
How to Prevent SQL Injection in PHP
Visual Studio Code Editor
How to Install Visual Studio Code Editor in Ubuntu & Debian
Python – Check If File or Directory Exists
Ternary Operator in Java
What is Ternary Operator in Java with Examples
exclude specific packages from Yum Update
How to Exclude Specific Packages from Yum Update
How To Exclude Packages from Apt-Get Upgrade
How to Get Shell Access to Running Docker Container
Top Tips to Make Your Digital Agency Stand out
Visual Studio Code Editor
How to Install Visual Studio Code Editor in Fedora and CentOS
SUBSCRIBE NEWSLETTER!

Email address: 
Your email address

Sign up
All rights reserved. © 2017 TecAdmin.net. This site uses cookies. By using this website you agree our term and services Hosted @DigitalOcean

