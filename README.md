# InfinitePlaceAnarchy2019 - An open source fork of https://rplace.live.
the outfit8tsb.github.io has been ended due to it's limitations.
it will be continued on rplace.live as a dual palette canvas called january 1st.
"Alone you can create something, but together, you can create something bigger" (or something like that)

**Site link: https://outfit8tsb.github.io/**
Thanks to Zekiah-A for Making original https://rplace.live.
When 2023: i was playing that masterpiece i made void disappear via my operation.
at 2024: turkey has overtook everything.
and after that: the color reset.
so that's why it was created as a fork.
message to turks who overtook everthing:
All Of You are Eliminated from My Shooooaw. Foreva. - two, tpot 11 by kyooby
 
![https://rplace.live running on firefox as of 18/4/2022](site_demo.png)
at site demo: Cave Story Got Overwritten by FN or Something and Has Disappeared.
We Cannot Take It Anymore Since Cave Story Charathers Are Now Mascot Of Infinite Place Anarchy 2019.
we are recovering this Site Demo as a offline canvas
and we will take revenge on who overwritten this.
Let's Nuke Em On here.
1.
Delete Loading Screen
Press F12
and Delete this to connect to the Offline Canvas! 
```
<div id="loadingScreen" style="opacity: 1; display: flex;">
            <img src="images/rplace-offline.png" style="position: absolute; width: 128px; height: 128px; z-index: 22;">
            <canvas id="waitingGameCanvas" style="width: 100%; height: 100%; z-index: 21;" width="1112" height="966"></canvas>
<input placeholder="Enter IP" onclick="this.focus()" onkeypress="if(event.keyCode==13){let a = localStorage.servers?localStorage.servers.split('\n'):[];if(a.length>9)a.pop();a.unshift(this.value);localStorage.servers=a.join('\n');wsinit(this.value)}" style="display: block;text-align:center;margin: auto;width: 300px;max-width: 80vw;margin-bottom:30px;">
	    <div id="connproblems" style="opacity: 1;">
                <span translate="connectionProblems">연결에 문제가 발생하셨나요?</span>
                <a onclick="localStorage.clear(); history.pushState(null, '', location.origin)" href="" translate="tryClickingHere">try clicking here</a>
                <br>
                or tweet us
                <a href="https://twitter.com/rplacetk">@rplacetk</a>
            </div>
            </div>
```
2. Place Pixels Infinitely Where the Ones Who Destroyed Cave Story
3. Draw A Gigantic BFDI / Cave Story / Infinite Place Anarchy 2019 Logo!
4. Nuke EM! NUKE EM ALL!!!
5. NUKE EM ALL YEAH YEAH YEAH! DELETE THEM ALL! YEAH YEAH YEAH! SO YOU CAN AVENGE CAVE STORY! SO YOU CAN AVENGE CAVE STORY! - Pencil
i knew kai cenet fans vandalized Cave Story Drawing on r/place 2022, kai cenet is not welcome here when countdown at 7.19 is over
*Feel free to contribute!*

# custom canvas
To set up your own custom canvas to be played on here, 
we have made a guide at our [Manual](MANUAL.md).
we also provide the system to connect any canvas via TKOfficial.


# Development

Forks of this project should either:
- Connect to the same server, that is, wss://server.rplace.live:443
- Or use the same app, that is, https://rplace.live

This project is licensed under the GNU LGPL v3, out of goodwill we request forks are
not run commercially (That is, they should not generate more than the cost of server upkeep).

### For example,

- My app (`fork-of-a-place.tk`) connecting to `wss://server.rplace.live:443` [✅ Cool, non-commercially]
- i implemented that but it didn't WORK.

### Testing:
 - While in theory, all dependencies should be installable using `bun install` within the root directory. Some
 modules, such as skia canvas may have dependency issues using the bun package manager. It is reccomended you
 also run `npm i` to ensure all dependencies, such as n-api v6 are installed.
 - The server can be run with `bun run server.js` in the root directory of the project.
 - You can use a simple HTTP server, such as the npm static-server module to test the client with a local server. For example, `npx static-server --cors='*'`
 
For more information on the game's protocol, look to the [protocol documentation](PROTOCOL.md).

### Also see:
 - [bun vscode extension](https://marketplace.visualstudio.com/items?itemName=oven.bun-vscode)
