[![Build Status](https://ci.cloudnetservice.eu/buildStatus/icon?job=CloudNetService/v2-notifysystem/master)](https://ci.cloudnetservice.eu/job/CloudNetService/job/v2-notifysystem/master)
[![star this repo](http://githubbadges.com/star.svg?user=CloudNetService&repo=v2-notifysystem)](https://github.com/CloudNetService/v2-notifysystem)
[![fork this repo](http://githubbadges.com/fork.svg?user=CloudNetService&repo=v2-notifysystem)](https://github.com/CloudNetService/v2-notifysystem/fork)
[![GitHub license](https://img.shields.io/github/license/CloudNetService/v2-notifysystem.svg)](https://github.com/CloudNetService/v2-notifysystem/blob/master/LICENSE)

[![DepShield Badge](https://depshield.sonatype.org/badges/CloudNetService/v2-notifysystem/depshield.svg)](https://depshield.github.io)
[![GitHub issues](https://img.shields.io/github/issues/CloudNetService/v2-notifysystem.svg)](https://github.com/CloudNetService/v2-notifysystem/issues)
[![GitHub contributors](https://img.shields.io/github/contributors/CloudNetService/v2-notifysystem.svg)](https://github.com/CloudNetService/v2-notifysystem/graphs/contributors)
[![Github All Releases](https://img.shields.io/github/downloads/CloudNetService/v2-notifysystem/total.svg)](https://github.com/CloudNetService/v2-notifysystem/releases)
[![GitHub release](https://img.shields.io/github/release/CloudNetService/Cv2-notifysystem.svg)](https://github.com/CloudNetService/v2-notifysystem/releases)


# Notify System | The Cloud Network Environment Technology 2 Notify System
![Image of CloudNet](https://cdn.discordapp.com/attachments/325383142464552972/354670548292206594/CloudNet.png)

This is the Notify System for CloudNet 2.2.0
 

 ### Support
 
  * Spigot-Support » 1.7.10 - 1.14
    * PaperSpigot, TacoSpigot, Hose, Torch
  * BungeeCord-Support » 1.7.10 - 1.14
    * Flexpipe, HexaCord, Waterfall, TraverTine
    
### Discord
 *  [Discord Invite](https://discord.gg/CPCWr7w)
 
### Developer
If you would like to contribute to this repository, feel free to fork the repo and then create a pull request to our current dev branch. 
  
Maven:
```xml
<repositories>
    <repository>
        <id>cloudnet-repo</id>
        <url>https://cloudnetservice.eu/repositories</url>
    </repository>
</repositories>

<dependencies>
    <!-- Spigot/BungeeCord -->
    <dependency>
        <groupId>eu.cloudnetservice</groupId>
        <artifactId>NotifyPlugin</artifactId>
        <version>1.0-SNAPSHOT</version>
        <scope>provided</scope>
    </dependency>
     <!-- CloudNet Core -->
    <dependency>
        <groupId>eu.cloudnetservice</groupId>
        <artifactId>NotifyModule</artifactId>
        <version>1.0-SNAPSHOT</version>
        <scope>provided</scope>
    </dependency>
</dependencies>
```