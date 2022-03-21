---
layout: post
title: "Setup Android Studio SDK Environment (MacOS)"
tags: android
---

1. Open terminal
2. `nano ~/.bash_profile` or `nano ~/.zshrc`
3. export sdk

``` bash
export ANDROID_HOME=$HOME/Library/Android/sdk
export PATH=$PATH:$ANDROID_HOME/emulator
export PATH=$PATH:$ANDROID_HOME/platform-tools
export PATH=$PATH:$ANDROID_HOME/tools
export PATH=$PATH:$ANDROID_HOME/tools/bin
```
4. Test setup. `echo $ANDROID_HOME`
5. Done!