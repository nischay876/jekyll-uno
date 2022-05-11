---
title:  "How to make lavalink server"
mathjax: true
layout: post
categories: media
---

### Here’s how to properly setup lavalink on Windows, MacOS, or Linux


![sb](https://spring.io/images/spring-logo-9146a4d3298760c2e7e49595184e1975.svg)
 In this tutorial we will be setting up lavalink server! 🎉
Let’s get started.
Now, first thing first
# Setting up the enviroment
__To make a lavalink server, you will need a java 13 or greater, I recommend using Azul Zulu java 16 or 17.__ 
You can download & setup java by going to here: 
- [Linux](https://www.azul.com/downloads/?os=linux&package=jdk) (Make sure to get `zulu16-jdk` or `zulu17-jdk`)
   - [Ubuntu / Debian; APT Base](https://docs.azul.com/core/zulu-openjdk/install/debian)
   - [Rhel / CentOS / Oracle; RPM Base](https://docs.azul.com/core/zulu-openjdk/install/rpm-based-linux)
   - [Arch; I use arch btw.](https://aur.archlinux.org/packages/zulu-16-bin/)
- [MacOS](https://www.azul.com/downloads/?os=macos&package=jdk)
- [Windows](https://www.azul.com/downloads/?os=windows&package=jdk)
 
## **If you want to host lavalink in single click on [railway.app](https://railway.app?referralCode=nischay) you can just click this button**

[![Deploy on Railway](https://railway.app/button.svg)](https://railway.app/new/template/7zGhsO?referralCode=nischay)

## You can also use my Lavalink Server [www.freelavalink.ga](https://freelavalink.ga)

Once install you can verify it by doing `java -version`, the output should look something like this
``` 
openjdk version "16.0.2" 2021-07-20
OpenJDK Runtime Environment Zulu16.32+15-CA (build 16.0.2+7)
OpenJDK 64-Bit Server VM Zulu16.32+15-CA (build 16.0.2+7, mixed mode, sharing)
```
**Congratulations 🥳 you’ve got Java installed!**
# Setting up lavalink.jar
To get started, you need to download the lavalink.jar and application.yml It’s pretty simple!

There are 2 jars provided below, one is the original one from [freyacodes](https://github.com/freyacodes) and one custom one which has alot more features than the original one
## Lavalink Jar download
- [Original Jar](https://github.com/freyacodes/Lavalink/releases/tag/3.4)
 [`https://github.com/freyacodes/Lavalink/releases/tag/3.4`](https://github.com/freyacodes/Lavalink/releases/tag/3.4)

- [Dev Jar](https://ci.fredboat.com/repository/download/Lavalink_Build/.lastSuccessful/Lavalink.jar?guest=1&branch=refs/heads/dev)
 [`https://ci.fredboat.com/repository/download/Lavalink_Build/.lastSuccessful/Lavalink.jar?guest=1&branch=refs/heads/dev`](https://ci.fredboat.com/repository/download/Lavalink_Build/.lastSuccessful/Lavalink.jar?guest=1&branch=refs/heads/dev)
- [Custom Jar](https://drive.google.com/file/d/1XTJMNUYzYTYOKBMzOAoqo8v28Sqe3O9V/view)
 [`https://drive.google.com/file/d/1XTJMNUYzYTYOKBMzOAoqo8v28Sqe3O9V/view`](https://drive.google.com/file/d/1XTJMNUYzYTYOKBMzOAoqo8v28Sqe3O9V/view)

## application.yml download
- [Lavalink Jar application.yml](https://github.com/freyacodes/Lavalink/blob/master/LavalinkServer/application.yml.example)
- [Custom Jar application.yml](https://drive.google.com/uc?id=1p2-pmPQUh3cJXcDjrlMYSSWPf1D0WgZA)

Once you’ve downloaded the jar and application.yml file, you can simply edit the application.yml port and password to your preferences.
Now last step is to move both into a single folder, then open a terminal to that folder using `cd`
 [How to use cd in windows](https://www.howtogeek.com/659411/how-to-change-directories-in-command-prompt-on-windows-10/)

 [How to use cd in mac](https://www.macworld.com/article/221277/command-line-navigating-files-folders-mac-terminal.html)

 [How to use cd in linux](https://linuxize.com/post/linux-cd-command/)

Then run it by doing java -jar Lavalink.jar or if you wanna limit it to only using X amount of ram you can do `java -XmxXG -jar Lavalink.jar` I.e. `java -Xmx2G -jar Lavalink.jar`
and you should get an output similar to this:

```bash
[root@oggy-testsrv lavalink]# java -Xmx2G -jar Lavalink.jar
2021-12-03 04:22:25.402  INFO 1826146 --- [           main] lavalink.server.Launcher                 :

       .   _                  _ _       _    __ _ _
      /\\ | | __ ___   ____ _| (_)_ __ | | __\ \ \ \
     ( ( )| |/ _` \ \ / / _` | | | '_ \| |/ / \ \ \ \
      \\/ | | (_| |\ V / (_| | | | | | |   <   ) ) ) )
       '  |_|\__,_| \_/ \__,_|_|_|_| |_|_|\_\ / / / /
    =========================================/_/_/_/

        Version:        3.3.2.3
        Build:          1239
        Build time:     31.08.2021 17:26:20 UTC
        Branch          main
        Commit:         2ad6b46
        Commit time:    31.08.2021 17:17:13 UTC
        JVM:            17.0.1
        Lavaplayer      1.3.93-original
```
“Help, I’ve tried the steps above but It doesn’t work.” If you’ve followed this entire guide and It doesn’t work, then please contact me on my discord server **[dsc.gg/oggys](https://dsc.gg/oggys) , [discord.com/invite/N28ZrdrhtA](https://discord.com/invite/N28ZrdrhtA)** and I’ll help you out. and also provide the following information:
- Which distro you are on
- What java version are you using
- What hosting provider you are using
- Don’t just say “doesn’t work”. Describe your problem in details

# And that’s it! You’ve installed lavalink! 🎉🥳 

Thank you for reading, have a great day!
- Discord Server - **[discord.com/invite/N28ZrdrhtA](https://discord.com/invite/N28ZrdrhtA)**
- Social Links - **[www.oggy.ga](https://www.oggy.ga)**

---
