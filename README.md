# Discord-Tricks-Hacks
JS code snippets to get special stuff in Discord Desktop or in WEB Browser by just pasting codes in Console.
- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - 
⚠ **DISCLAIMER:** 

This repo is strictly only for **EDUCATIONAL & TESTING Purposes**, I does not encourage / Promote / Support any Terrorism / Illegal / Harmful activities using any of these hacks. I'm not responsible for any punishments, you perform / use this at your own responsibility, using code snippets of this repo in unofficial way, may result in your account being banned / disabled / terminated.



# Console Hacks:

✔ **How to Use this Snippets** 👉

1: Open your Discord in web browser or in Desktop App.<br />
2: Press Ctrl+Shift+I on your PC [for mac users can press Opt+command+I]<br />
3: Active the console tab if not.<br />
4: Paste the snippets in the console.<br />
5: Press "Enter" and Run the script.<br />

<sub><sup>_🎉 This Scripts legitimately gives you client-side stuffs._</sup></sub>
#

🚩 **Get All Badges:** V 1.1
```diff
+ This script gives you all discord badges on your client and you can access different badges by changing [flag] in the snippet.
```
![alt text](https://github.com/pixelboiworld/Discord-Tricks-Hacks/blob/main/Images/discord_badges.jpg?raw=true)
```js
let flag = '24';
window.webpackChunkdiscord_app.push([
    [Math.random()], {}, (req) => {
        for (const m of Object.keys(req.c).map((x) => req.c[x].exports).filter((x) => x)) {
            if (m.default && m.default.getCurrentUser !== undefined) {
                return m.default.getCurrentUser().flags = -flag;
            }
			 if (m.default && m.default.getCurrentUser !== undefined) {
                return m.default.getCurrentUser().public_flags += flag;
            }
        }
    }
]);
```
📺 See the Tutorial video by BrandHax on YouTube here: [Watch Here](https://youtu.be/McmFAGhCM1M)
#

🚩 **Get System Tag:** V 1.0
```diff
+ This script gives you system tag on your profile.
```
![alt text](https://github.com/pixelboiworld/Discord-Tricks-Hacks/blob/main/Images/system_tag.jpg?raw=true)
```js
window.webpackChunkdiscord_app.push([
    [Math.random()], {}, (req) => {
        for (const m of Object.keys(req.c).map((x) => req.c[x].exports).filter((x) => x)) {
            if (m.default && m.default.getCurrentUser !== undefined) {
                return m.default.getCurrentUser().system = true
            }
            if (m.getCurrentUser !== undefined) {
                return m.getCurrentUser().system = true
            }
        }
    }
]);
```
#

🚩 **Get Bot Tag:** V 1.0
```diff
+ This script gives you bot tag on your profile.
```
![alt text](https://github.com/pixelboiworld/Discord-Tricks-Hacks/blob/main/Images/bot_tag.jpg?raw=true)
```js
window.webpackChunkdiscord_app.push([
    [Math.random()], {}, (req) => {
        for (const m of Object.keys(req.c).map((x) => req.c[x].exports).filter((x) => x)) {
            if (m.default && m.default.getCurrentUser !== undefined) {
                return m.default.getCurrentUser().bot  = true
            }
            if (m.getCurrentUser !== undefined) {
                return m.getCurrentUser().bot = true
            }
        }
    }
]);
```
📺 See the Tutorial video by BrandHax on YouTube here: [Watch Here](https://youtu.be/rl19_V7MZiA)
#

🚩 **Get server Verified Tag:**
```diff
+ This script add Discord verified tag to your server.
This snippets needs [SERVER_ID].
[Click Here](#How-to-get-Server-ID-?): how to get any discord server id?
```
![alt text](https://github.com/pixelboiworld/Discord-Tricks-Hacks/blob/main/Images/discord_server_verified_badge.jpg?raw=true)
```js
window.webpackChunkdiscord_app.push([
    [Math.random()], {}, (req) => {
        for (const m of Object.keys(req.c).map((x) => req.c[x].exports).filter((x) => x)) {
            if (m.default && m.default.getGuild !== undefined) {
                return m.default.getGuild('SERVER_ID').features.add('VERIFIED')
            }
            if (m.getCurrentUser !== undefined) {
                return m.getGuild('SERVER_ID').features.add('VERIFIED')
            }
        }
    }
]);
```
#

🚩 **Get server Partnered Tag:**
```diff
+ This script add Discord partnered tag to your server.
```
![alt text](https://github.com/pixelboiworld/Discord-Tricks-Hacks/blob/main/Images/discord_server_partnered_badge.jpg?raw=true)
```js
window.webpackChunkdiscord_app.push([
    [Math.random()], {}, (req) => {
        for (const m of Object.keys(req.c).map((x) => req.c[x].exports).filter((x) => x)) {
			if (m.default && m.default.getGuild !== undefined) {
                return m.default.getGuild('SERVER_ID').features.add('PARTNERED')
            }
            if (m.getCurrentUser !== undefined) {
                return m.getGuild('SERVER_ID').features.add('PARTNERED')
            }
          
        }
    }
]);
```
### How to get Server ID?

#
More snippets comming soon, This repo already in construction...
