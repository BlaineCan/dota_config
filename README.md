# My Dota 2 Config File

## What is this?
This is my config file that I use in the popular steam title, Dota 2.

## Why would I want it?
By default, damage received/ dealt is represented by a white area on the health bar. After a short delay, the white bar disappears and the health is updated.
Personally, I do not like. I think it's easier on the eyes to see the damage displayed without the delay.  
## Where do I put it?
First, grab the autoexec file from this repo.
```bash
git clone this_repo_name
```

place this file into your dota game config directory
```bash
$PATH:/steamapps/common/'dota 2 beta'/game/dota/cfg && mv $PATH:/autoexec.cfg $PATH:/steamapps/common/'dota 2 beta'/game/dota/cfg  
```

Finally, setup launch option for dota 2 to use the config file.
```
+exec autoexec
```
