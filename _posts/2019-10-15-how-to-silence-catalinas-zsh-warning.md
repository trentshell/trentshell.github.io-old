---
layout: post
title: "How to Silence Catalina's zsh Warning"
date: "2019-10-15"
---
MacOS 10.15 Catalina came out, and changed up the default shell from bash to zsh. I don't have a ton of defaults that would break if I moved over, but I decided that at this point there wasn't anything I'd lose my maintaining my current setup and `.bash_profile`. The annoying part, though, is that every time I open Terminal now it helpfully reminds me that bash is no longer the default. Here's the official Applie fix if you want to silence the warning.
 
> If you invoke the bash shell while macOS Catalina is configured to use a different shell, you'll see a message that the default interactive shell is now zsh. To silence this warning, you can add this command to ~/.bash_profile or ~/.profile:
> `export BASH_SILENCE_DEPRECATION_WARNING=1`

Source: [Use zsh as the default shell on your Mac](https://support.apple.com/en-us/HT208050)