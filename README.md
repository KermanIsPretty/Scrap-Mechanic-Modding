# Creating your SM Development Enviorment
> This tutorial is written for Visual Studio Code

**Requirements**
 1. [Visual Studio Code](https://code.visualstudio.com/) 
 2. [Lua Language Server extension](https://marketplace.visualstudio.com/items?itemName=sumneko.lua) ([github](https://github.com/sumneko/lua-language-server))

## Step 1
[Download](https://scrapmechanic.com/api/lua.zip) and extract sm.lua

## Step 2
Move the sm.lua to a memorable locaiton.

## Step 3
Open visual studio code and navigate to the settings of the Lua language server.

## Step 4
Scroll in the settings until you see library.

## Step 5
Click add item and type in the full directory path of your memorible location followed by 
``sm.lua``
An example would be
``E:\SM-Docs\sm.lua``

## Step 6
Press ok or enter when you are finished entering the library location.

## Step 7
Open your mod folder or what scripts you want to edit.

## Step 8
Congratulations! You now have the [SM docs](https://scrapmechanic.com/api/index.html) when you write code.

# FAQ

## Limitations
1. Content or custom paths will not resolve.
2. Does not error/warn when using server/client function in the wrong scope.
3. Will still require some understanding of how Scrap Mechanic works.

## Missing some Functions?
You will need to add other libraries (see step 3 - 6).

 1. Util - ```<REPLACE WITH SM INSTALL PATH>\Survival\Scripts\util.lua```
 2. AnimationUtil (tools) - ```<REPLACE WITH SM INSTALL PATH>\Data\Scripts\game\AnimationUtil.lua```

## I need help!
1. Try joining and asking the [Scrap Mechanic Modding Discord](https://discord.gg/SVEFyus)
2. Try asking on [r/ScrapMechanic](https://www.reddit.com/r/ScrapMechanic/)
3. Ask a friend.
