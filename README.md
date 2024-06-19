<p align="center">
<h1> NOTICE: SkriptBE will be Migrating to Zonasky\Zona soon </h1>	
	<b>Port of Bukkit Skript for PocketMine-MP</b>
</p>

Skript is a plugin for PocketMine-MP, which allows server owners and other people to modify their servers without learning PHP. You can load scripts from Bukkit plugin version.

# What is Skript?
Skript is a plugin that allows you to customize Minecraft's mechanics with simple scripts written in plain English sentences. 

# Requirements
SkriptBE requires latest PocketMine-MP.
# What's New:
> SkriptBE has been updated from PM3 to PM5. 2 new Events: SleepEvent and EatEvent. Open issues if found to squash bugs!
# Download
You can download latest version plugin form <a href="https://poggit.pmmp/p/SkriptBE">here</a>

# Install
Download plugin and put to plugins folder.

# How to use
Install plugin and drop scripts to folder **plugin_data/SkriptBE/scripts** (script file name must be end in .sk). Run server. You can see loaded scripts by command **/skript list**. In folder **plugin_data/SkriptBE/scripts** is scripts you can load it when you remove -- from file name.

# TO-DO
 - [x] configs and files support,
 - [ ] control structures eg. if, else (50 %),
 - [ ] variables (50 %),
 - [ ] entity support,
 - [ ] implement api,
 - [ ] add support for iProtector,
 - [x] boss bars,
 - [ ] mysql, sqlite3,
 - [ ] curl support,
 - [ ] more functions,
 - [ ] new events,
 - [ ] implement regions,

# Examples
Basic commands:
```
command /hello:
  permission: hello.permission
  permission message: You can not use this.
  description: "description for /hello command"
  trigger:
    send "<red>Hello"
```

Events:
```
on join:
    broadcast "&a%player% join to server!"
```

```
on quit:
    broadcast "&e%player% left from server!"
```

Timers:
```
every 5 minutes:
    broadcast "This plugin is great"
```

# Documentation
The documentation for this plugin is the same as for its Java versions. You can see it under the <a href="https://skriptlang.github.io/Skript/index.html">link</a>

# License
This project is licensed under GPLv3.
