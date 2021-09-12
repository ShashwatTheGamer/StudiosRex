# Long Term Scripter

> ### Payment

There are 2 options for payment.
1. One time payment; 10k robux; group funds
2. Monthly payment; 2-5k robux; group funds

> ### Task

You have been given the access to the game. You can find it in `Roblox Studio > Group Games > Studios Rex > Minigame Simulator (there are 2 games with the same name, choose the one with the logo)`

In there, you can have 1 days time to understand all the scripts, and codes. In the `workspace`, you can see a `string value` with `RoundScript` inside it. It has about 1000 lines. I know its a lot, but its just repetitive code. 

You must have knowledge about `config scripts` they are just `module scripts` with a `table with variables` in it. Eg:
```lua
{
	"RoundTime" = 10,
	"VotingTime" = 20
}
```
These have the variables inside it which will be used by the scripts. It should be named `config` and kept in `ServerScriptService`.
Also note, the currencies should be included in the `config`.
Also, there are some variables like the `RoundDurationTime` that will differ from minigame to minigame. You can keep those variables inside the map model with a `config script` for each map.

Also, I realized that the previous scripter didn't do a great job as he kept the maps in `Lighting`. You are free to move any model/folder at the right places. Eg `maps` to be kept inside the `ServerStorage`. 

We also need map voting system. If you have played Piggy, you will notice that there are 3 levels of voting. In our game, the voting levels are:
1. Minigame
2. Map
3. Difficulty
Also, if there are not 2+ maps, or the difficulty isnt defined, the voting for that shouldnt pop up, I mean like, if `HotDogRunner` for example is chosen, and if it doesnt have 2+ maps, then it shouldnt ask choose map, it should only ask chose difficulty.

Now, what exactly is `Map` and `Difficulty`? I need you to make the script so that if 1 minigame have multiple maps, like the minigame `FloodEscape` can have multiple maps like the `city` and `forest`, the script should only spawn that map (after voting).

Difficulty is just `Easy`, `Intermidiate` and `Hard`. In each map's `config`, there will be the difficulty defined, like in the `FloodEscape` minigame, the difficulty can be how much speed does the water have. or for the `CrossTheRoad` it can have how fast the cars must go, and car spawning rate, etc. I hope you can understand.

The folder structure of the maps can be as follows:
``` text
Maps > [Minigame name] > [Map] > config
                               > build
```

The teleporting part, rewards, winners, etc should also be scripted.

Also, there should be a cutscene should the minigame map before the minigame starts.
And a cutscene showing the top-3 player too.

There are 19 minigames to rescript, they should be neat, modular (each minigame in a different module script) with configs.

I also need a few, random coins spawning in the maps, be it the minigame or lobby, rarely and a few coins spawning that players can pick up.

Also, make some of the moving parts as local script to avoid lag. Also, this is NOT necessary for all moving parts. 

Some of scripts are also inside the map itself, for moving parts etc. You can see how you manage it.

1 last thing, if you have hear about the `Map Spawning Building Tweening Animation ` put that. If not, let me explain. It is when a map spawns, each and every part inside the model, flys in the air, tweens, and then comes into place. Its kinda complicated, so you can take this script from here https://www.roblox.com/library/6133699812/Twins-Tycoon-Kit-2-0.

This is the script of a tycoon, there is a script called purchasehandeler in that, the function animateBuildingIn and related functions, u can use. It should be easy.

That's all you need to script. You will get the next task once you complete this.

> ### Deadline

At max 20 days for this task. Average days are 15.
