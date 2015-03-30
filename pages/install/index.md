---
layout: page
title: "Installation"
date: 2015-01-16
modified:
excerpt: "Install Civilization IV: A New Dawn"
tags: []
image:
  feature: installation.jpg
---

<section id="table-of-contents" class="toc">
  <header>
    <h3>Overview</h3>
  </header>
<div id="drawer" markdown="1">
*  Auto generated table of contents
{:toc}
</div>
</section><!-- /#table-of-contents -->


_**This expansion pack is in continuous development, so expect updates every month.**_

<hr>
# Standard installation

<center><a target="_blank" href="http://sourceforge.net/projects/anewdawn/files/latest/download?source=files"><img src="{{ site.url }}/images/download_small_green.jpg" width="50"  height="50" border="0" /><strong>DOWNLOAD INSTALLER NOW</strong></a></center>
  <br>
<a target="_blank" href="http://www.moddb.com/mods/rise-of-mankind-a-new-dawn">Alternative: the installer can also be downloaded from our Moddb page.</a>

**Installation instructions**
: 

- Make sure you have Civilization IV - Beyond the Sword installed and patched to 3.19 or have the steam version (automatically patched).
- Download the installer.
- Execute it.
- Select the installation language (you can change it later).
- Select the installation folder (default is recommended).
- If you are absolutely sure than you already have MSVC2010, you can untick the box, but otherwise, let it ticked.
- The installer creates shortcuts on the desktop and in the start menu by default.
- Once finished, the launcher will start and you can enjoy the expansion !

The launcher can be use to select textures sets, graphical formations option and update the game easily. [_Please refer to the FAQ for further configuration questions._]({{ site.url }}/pages/faq/)
 <br>
**How to update the game?**
: When an update is released, the launcher will highlight a yellow "update" button. All you have to do is to click on it, check what have changed and press "update", then wait.
If you don't have internet on that PC, either redownload the updated installer or stay tuned as a small offline updating tool should appear on that website in the next weeks !

<br>
**Can I download an older version of the game?**
: We keep a track of old versions [_on our server_](http://sourceforge.net/projects/anewdawn/files/). Please note that <u>these versions are totally unsupported</u>.

 <br>
**Special note for Steam users**
: A while ago, the online internet service Gamespy has shut down, and Firaxis have released a patch to be able to continue to play online using Steam. While this is a wonderful news, they also introduced a bug which prevents the religion icon to be displayed into the score (at the right bottom of the ingame screen). Yet, they allow to use the old patch.

- Show your steam games list
- Right click on "Sid Meier's Civilization IV: Beyond the Sword", then properties.
- Go in the "Betas" tab, then select "original_release_unsupported" in the dropdown menu.
- The game will revert back to the old patch (you can select back "none" if you want to revert this move).

_**Note**_ : You won't be able to play in the matchmaker online with this Steam patch but you'll still be able to play by direct IP with your friends or with players with the CD version (v3.19).

<hr>
# Developer installation (SVN)[english]

We use SVN to ease the development. If you want to get involve, just follow these instructions:

 <br>
**Download the working copy**
:

- Download and install Tortoise SVN if you don't already have it ([Download page](http://tortoisesvn.net/downloads.html))
- Prepare a folder to contain your copy of the AND project, it will be known as your 'Working Copy.' This Working Copy will be the local directory on your machine but also it will be your 'image' of the central repository. Developers and contributors can make changes to the game through their folder and upload/contribute them. This folder essentially is like the hub that connects the changes you make (if your a developer) with the changes others make, and it all syncs together.
- Checkout from the repository to the folder you created in (2). This will get the current revision and make a permanent connection between your working folder and the repository. Assuming you have installed SVN as in (1), you can do this by right-clicking the directory in Windows Explorer and selecting 'Tortoise SVN/Checkout...'

When it asks you for the repository URL enter:

`svn://svn.code.sf.net/p/anewdawn/code/Trunk`

- To download future refreshes or uploads (aka Commits) from the AND2 development team you won't have to REdownload it all again, you simply right click on the 'working copy' and select 'svn update'. This will then proceed to only download the 'changed' or updated files and add any new ones in, so it will be much, much faster.
- After it's all copied you are up and running!

**Export the copy**
:

Now how to get the working copy into play?:

- Create an empty folder somewhere then..
- Right click (hold) and drag the folder of your 'working copy' to this newly created folder and when you let go of the right mouse button you can..
- Select the 'export versioned items here' option.
- Once its finished exporting your up to date mod into where you wanted it - move the result ( Rise of Mankind - A New Dawn ) folder into civ4/beyond the sword/mods 
