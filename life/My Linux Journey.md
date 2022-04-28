---
layout: meth
date: 2022-04-28
parent: life
---
# My Linux Desktop Journey
I've been using Linux desktop exclusively for about 3 months. It's really great, much better than I thought to be.

Before using Linux desktop, I've been using WSL (Windows Subsystem for Linux) for about 1 year. And as much as I enjoy it, it still has some limitations, for example, the lack of systemd and GUI support (Win11 sort of has it tho). The final push toward me using a full Linux desktop, was seeing a not so tech-savvy classmate using Ubuntu, almost exclusively. I was pretty impressed by the elegance of Ubuntu (now I know it's Gnome) at that time. So, in the winter vacation, when I had many time, I decided to give Linux desktop a try.

I have 2 computers, one gaming laptop which I use at my room, and another lighter and more portable one which I use outside of my home or dorm, like in classes, libraries or cafes. At first, I installed Kubuntu on both latops. Despite knowing the existence of other fancier distros, I still chose Ubuntu as I'm a beginner. But of course, instead of jumping right into it, I still researched a bit beforehand, and found that there's a thing call "DE", and the normal Ubuntu used Gnome while there are other Ubuntus that used other DEs. After learning that "KDE" is the best for customization, I decided to go with Kubuntu, and I love it.

## Migration of Daily Apps

Kubuntu is pretty stable, and KDE is a total beast. It really let you customize everything from windows decoration to docks to loading screen to keyboard shortcuts, really, everything.

KDE native apps are also so god damn good. The most life-changing one, is Okular. Long long time ago, I would use a cracked Adobe Acrobat Pro to do document markups. But the cracked version somehow broke one day, and I turned to Goodnotes as a result, which provides much better quality of life and more features. But Okular, is actually better than Adobe Acrobat Pro in almost every way. The document viewing experience is much smoother, the shortcuts are configurable, and the markup features are also better.  And as I do not have hand-writing heavy courses this semester, it becomes a perfect tool for me to do pdf reading and markups. In fact, it has become one of the main reasons for my inability to go back to live in Windows.

For other apps, some are better and some are worse than their Windows counterparts, but none is deal-breaking. To give some examples, Konsole is far better than Windows Terminal (which is a good app itself), Onlyoffice & Libreoffice is worse but still useable compared to Microsoft office. Flameshot is almost as featureful as Snipaste, but is much slower. Rclone is so barely liveable compared to native Google Drive Windows app, but is still, liveable. Pinta is pretty much the same as the little painter. I can't get a hole on Krita and Gimp tho. When I want to do some Photoshop related works, I still turn to Photopea. Good thing is that I don't do much 2D creation now (or ever). Same goes for video editing. I used to do a lot of it, with Adobe After Effects & Premiere Pro, but I haven't have the need to use them for a couple of months, so I still haven't done some exploration about the open source version of them, Davinci Resolve for instance.

### Evernote
There's an honorable mention tho, which is, Evernote. I basically do all my journaling (it's not exactly journaling, but the closest thing to describe it is journaling) there. (I also do some lightweight note-taking on there before, but I pretty much migrate all of them to other apps.) But Linux does not have a native Evernote app. It has a beta one tho, which you'll have to apply to be the beta tester to get the Linux app, but they have yet to approve my application.

So, to use Evernote on Linux, all you can do is use the shitty web version. There are 2 web versions available, the legacy one and the v10 one. However the legacy one is not the like amazing legacy Evernote native app. No, far from it. It has minimal features. Some of the very essential features are even not available. It's pretty fast tho. As for the v10 version, it's pretty featureful, pretty much the same as the v10 native app I think (I mean, v10 is all about unifying the codebase so is pretty natural), but just like the v10 apps on every other platform, it is god damn slow. Doing every single operation takes a minimum of 5 seconds. To make things worst, every few hours, it automatically logs you out, and clear all the cache or whatever I think. After you log back in, you have to wait for like 5 minutes to let it load all your entire database (I have so many notes so it really takes a long while). But does it really load your entire note data? Hardly. It still takes 5 seconds to open a note, so idk what does it really loads in that 5 minutes startup phase. The indexes maybe?

Anyway, it's still liveable, but barely. The reason I'm still willing to put up with the shit of Evernote is that, there are no viable alternatives. If all I use is desktop, then sure, Evernote isn't in the top 5. But considering the compatibility of every platform and every format, Evernote is undeniably the No. 1. The **legacy** Android version is just so good, so fast and so useful. (The v10 versions are still shits tho.) None of the mobile version of new flashy note-taking apps can reach the height of Android legacy Evernote. For example, compared to Android legacy Evernote, Joplin is not as featureful, Nimbus is not as smooth, Notion is not as fast, while Obisidian and Roam are just not compatible to the mobile form factor.

## Endeavour
I didn't allocate too much disk space for my Kubuntu partition on my portable laptop, and soon I found that it's a bit small. I go to Windows and clear out many space with the help of WizTree, ended up with 100+GB free space. And then I thought, why not try a new distro? I've always want to be part of the Arch btw cult. Wasn't that a good chance to join? 

So, after some research, I decided to give EndeavourOS a try, as I'm still not advanced enough to install everything myself, but I don't want to use Manjaro either, which seemed to be bloated, with a problematic delayed packaging system and a reddi-powermod like maintainer.

I used KDE as my DE at first, and for some reason, it was super laggy. After trying to solve it with no result, I gave XCFE a try. After tinkering a bit, I gave up as I don't think the ugliness of XCFE is solvable. Everything was still laggy on XCFE also. Then I turned to i3, a pure WM. Spent many time configuring it, but everything was still laggy on it.

So, I thought, maybe the iso I downloaded is broken or something, so I decided to do a reinstall. And this time, it's smooth as fuck (still using KDE). One thing I noticed is that, when I switched the power profile to "power save", it became just as laggy as the previous installation, and when I switched to "balanced" or "performance", it would be smooth as fuck. So maybe, I installed tlp or something, and it automatically made my computer always in powersave mode or something, making it super laggy.

Anyway, I'm enjoying my sweet little Endeavour very much. Pacman + yay is just godsend.

The initial phase of using EndeavourOS was not smooth for me tho. Even though it provided a GUI installer, installing many essential packages for you, there were still many essential packages for my usage that were missed. Notable examples are, some KDE addons, Bluetooth manager, and Chinese inputs. All took me a while to research and found out what was missed. Good thing is that I documented all in my CollegeNotes, so in my 2nd installation, everything went smoothly.

## Kubuntu vs. Endeavour
So I've used both Kubuntu & EndeavourOS exclusively now, and even though I use KDE on both with almost the same config files, there are still some notable differences.

### Package Manager
Many essential packages are installed on Ubuntu already, which is nice, so when I'm in my network lab class, I prefer to log into Kubuntu. But when I'm doing my own things. I still prefer EndeavourOs, as I have more time to search for errors I encountered, and that pacman+yay is just better than apt.

When you want to install a 3rd-party app on Ubuntu, many times you'll have to add a PPA or something, including some sort of keys which I still don't understand. You'll end up having to enter so many lines of commands just to install one package, and it also increase the number of displayed lines of your `apt update`, making it looks so bloated. Well, either this, or install a snap ir flatpak version, if available.

But in Arch-based distros, all you have to do is do `yay -S <package>`. Yes, just one and single line. Saving so much hassles. I don't know and don't really care about the differences of the security aspect of it, all I care is the convenience, which AUR packages outperform Ubuntu PPAs greatly.

Pacman is also faster looks nicer than apt, with more elegant syntaxes.

### Release Cycle
I pretty much only use KDE, so I can only speak for it, but KDE apps on Endeavour have visibly more features than those on Kubuntu.

### Stability & Quality of Life
Even though Endeavour is rolling release, I haven't really encountered any unstable moment during the time I spent with it. In fact, it is in many ways more stable than Kubuntu. The most notable example is that, on my main laptop, I use Kubuntu development version, and it is the most unstable thing I've ever used. KDE literally crashed every few minute, generating glitches after glitches, and for some reason, even after Ubuntu 22.04 LTS is released, meaning that my dev version was automatically converted into the LTS version, the glitches and crashes are still there. Meanwhile the normal Kubuntu version on my portable laptop never has any problem.

However, the touchegg (a program mapping touchpad gestures into keys) on the Kubuntu on my protable laptop, never works probably. It works, but you'll have to swipe very long for it to work. On the Endeavour on my protable laptop and the Kubuntu on my main laptop tho, touchegg is very smooth, almost as smooth as the Windows gestures.

So, everything considered, the quality of life on Endeavour is higher than on Kubuntu, tho not by much. But even the quality of life is the same, I would still use Endeavour as I can proudly say I use Arch btw and relate to the Arch memes.