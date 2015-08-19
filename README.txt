Final Frontier Plus DLL Source Code
-----------------------------------

This repo contains everything needed to build the CvGameCoreDLL library for
the Final Frontier Plus mod for Civilization 4: Beyond the Sword.

Compiling:
----------

You need some dependencies, and you need to be building on a Windows system.
I recommend installing git and adding it to your PATH, but you can use
a GUI wrapper for git too if you'd prefer.

Visual Studio probably even has some kind of git integration although I've
never used it

The list of tools you need can be found here:
http://modiki.civfanatics.com/index.php?title=How_to_Install_the_SDK#Installing_the_Tools

Note that the correct version of the Platform SDK may be difficult to acquire 
on Windows > 7!

A Visual Studio 2010 project/solution is included. But, if you'd prefer, you can
just run "make" in the command prompt.

Contributing:
-------------

We're more than happy to take pull requests. Please do your work in a
different branch and show that you've tested things. Because of the size
of the Civ 4 codebase, it would be appreciated if you commented the sections
of the code that *you* modified and for what purpose.

Discovering Changed Files:
--------------------------

While the full source code is maintained here, so it can be easily cloned
and compiled, we only ship the changed files in the official release.

At the moment, you can run the following git command in a terminal to get
a list of these files.

"git diff --name-only bts_3.19 HEAD"

That should output a list of the files that have changed since the project
began.

A script that does this automatically will eventually be written.

(Obviously, you can ignore changes to the documentation, gitignore, etc.).

License:
--------

Final Frontier Plus is as "open source" as a mod of a proprietary video game
can get. In a nutshell that means you are welcome to use any assets (code,
art, etc.) created by Final Frontier Plus contributors in other Civilization
IV mods (or elsewhere, should you really want to).

Firaxis and 2K own Civilization 4.

"Final Frontier" is a scenario created by Jon Shafer for Civilization IV:
Beyond the Sword when he was employed by Firaxis Games.

"Final Frontier Plus" is an unofficial modification built by TC01 and God-Emperor, 
among other contributors (Please see the CREDITS.txt file in the main repo). 

None of the above parties are liable for any damages caused by any part of
Final Frontier Plus.
