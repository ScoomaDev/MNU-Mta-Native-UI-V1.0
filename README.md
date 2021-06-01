![Opera Snapshot_2021-05-28_192354_www google com](https://user-images.githubusercontent.com/80770027/120027981-fbf09580-bfeb-11eb-9e33-701578c0b600.png)

███╗░░██╗░█████╗░████████╗██╗██╗░░░██╗███████╗  ██╗░░░██╗██╗
████╗░██║██╔══██╗╚══██╔══╝██║██║░░░██║██╔════╝  ██║░░░██║██║
██╔██╗██║███████║░░░██║░░░██║╚██╗░██╔╝█████╗░░  ██║░░░██║██║
██║╚████║██╔══██║░░░██║░░░██║░╚████╔╝░██╔══╝░░  ██║░░░██║██║
██║░╚███║██║░░██║░░░██║░░░██║░░╚██╔╝░░███████╗  ╚██████╔╝██║
╚═╝░░╚══╝╚═╝░░╚═╝░░░╚═╝░░░╚═╝░░░╚═╝░░░╚══════╝  ░╚═════╝░╚═╝


# MNU-Mta-Native-UI-V1.0

Created By [ScoomaAli](https://discord.gg/9bcuWJEnwd)

Idea From : FiveM

Game : Multi Theft Auto San andreas (MTA SA)

Version = V1.0

# WIKI SECITON

## !. Use this line in your client script to export NativeUI functions : 
```LUA 
local NativeUI = exports.NativeUI 
```

### - functions : 
# >CreatePool

``` lua
int CreatePool(string WindowTitle, string WindowDescription [, string backgroundFile,bool useBackSpaceClick] )

```
- **WindowTitle** : the text that will be showing in the window header 


![Opera Snapshot_2021-05-28_192354_www google com - Copy (2) - Copy](https://user-images.githubusercontent.com/80770027/120030727-b9c95300-bfef-11eb-8179-5a47195758d5.png)

- **Window Description** : will be showing ender the title


![Opera Snapshot_2021-05-28_192354_www google com - Copy (2)](https://user-images.githubusercontent.com/80770027/120030906-f2692c80-bfef-11eb-959e-c98237f0415b.png)


- **background file** : the path of the background image ("none" for hide it ot false for use the original)

![Opera Snapshot_2021-05-28_192354_www google com](https://user-images.githubusercontent.com/80770027/120031428-b2567980-bff0-11eb-93fa-328c0618473f.png)

- **use backspace button** : on player click the [backspace] thw window will be closed 
- **return** the window's id 

# >addTab

``` lua
int addTab(int parentWindowID ,string tabType, string tabText, string tabEvent[,table itemsTable] )
```

- **parentWindowID** : id of the parent window 

- **tabType** : type of the tab

| Type | Function |
| --- | --- |
| "button" | normal native button |
| "check" | check box button yes . no |
| "select" | a groupe of items : < item > | 

- **tabText** : tab text 

![Opera Snapshot_2021-05-28_192354_www google com - Copy](https://user-images.githubusercontent.com/80770027/120034554-2266fe80-bff5-11eb-9b0d-cddef9230e63.png)


- **tab event** : a event attached to tab , you need this in eventHandler

- **itemsTable** : [ only in "select" type ] , table of select items exemple : {"scooma", "ali", "mmg", 10, 50,10.5,false,true,nil}

 ![Opera Snapshot_2021-05-28_192354_www google com - Copy (3)](https://user-images.githubusercontent.com/80770027/120035279-395a2080-bff6-11eb-8be6-b0f0590c1c5e.png)
 
- **Return** : id of the tab

# >DeletePool

``` lua 
bool DeletePool(int windowID)
```
- **WindowID** : window id :)

#Events 
-Coming Soon  !


