# Discord-Tricks-Hacks
JS code snippets to get special stuff in Discord Desktop or in WEB Browser by just pasting codes in Console.
- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - 
**DISCLAIMER:** 

This repo is strictly only for **EDUCATIONAL & TESTING Purposes**, I does not encourage / Promote / Support any Terrorism / Illegal / Harmful activities using any of these hacks. I'm not responsible for any punishments, you perform / use this at your own responsibility, using code snippets of this repo in unofficial way, may result in your account being banned / disabled / terminated.



# Console Hacks:

✔ **How to Use this Snippets** 👉

1: Open your Discord in web browser or in Desktop App.<br />
2: Press Ctrl+Shift+I on your PC [for mac users can press Opt+command+I]<br />
3: Active the console tab if not.<br />
4: Pate the snippets in the console.<br />
5: Press "Enter" and Run the script.<br />
#

🚩 **Get All Badges:**
```diff
+ This script gives you all discord badges on your client and you can access different badges by changing flags in the snippet.
```
![alt text](https://github.com/pixelboiworld/Discord-Tricks-Hacks/blob/main/Images/discord_badges.jpg?raw=true)
```js
window.webpackChunkdiscord_app.push([
    [Math.random()], {}, (req) => {
        for (const m of Object.keys(req.c).map((x) => req.c[x].exports).filter((x) => x)) {
            if (m.default && m.default.getCurrentUser !== undefined) {
                return m.default.getCurrentUser().flags = -24;
            }
			 if (m.default && m.default.getCurrentUser !== undefined) {
                return m.default.getCurrentUser().public_flags += 24;
            }
        }
    }
]);
```
📺 See the Tutorial video by BrandHax on YouTube here: [Watch Here](https://youtu.be/McmFAGhCM1M)
#

🚩 **Get System Tag:**
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

🚩 **Get Bot Tag:**
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
#
More snippets comming soon, This repo already in construction...
