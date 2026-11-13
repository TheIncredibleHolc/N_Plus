# N+ PC Port

Greetings Ninjas!

This PC Port is a preservation project that allows people to play the 2008 XBLA version of N+, which is unavailable on the Xbox Marketplace and is becoming lost media. 
This recomp is based off the ROM provided in the N++ Discord. Because this is strictly a preservation project, new gameplay features outside the scope of the original game will not be added. 
Anyone wanting a new experience should **buy N++** and **wishlist N+InfinityTimesTwo** to support the devs!

Lastly, please direct all PC-Port questions and issues to @theincredibleholc. 
**Do not bug the N+ developers or the official N++ discord for support!**

__Features: __
- All original tutorials, levels, and DLC are available with Co-op gamemodes too.
- N+ game launcher allows you to easily see and configure settings and toggle QoL enhancements.
- "System Link" functionality has been repurposed to allow online peer-to-peer multiplayer. (Host **must** open UDP 1000 and 1001)
- New video options to allow up to 4K rendering and framerates beyond 60fps. (Via interpolation, physics still run at 60hz)
- SDL3 Input to allow KB/M or other branded controllers. (Playstation, Nintendo, even Rockband Drums if you really wanted)
- Discord Rich Presence integration, allows sending multiplayer invites and joining matches directly through Discord.
- Local profiles that save and track your episode progress with completion stats on the launcher. 
- Original Xbox 360 achievements unlockable with in-game notifications.
- In-game level builder supports playing your customs online. Players can also export their levels via launcher and send to others. 

__Requirements:__
- Windows 10 or higher OS
- SSE4.2 compatible processor, AVX2 preferred.

*If you love this game, support the devs!* [*Buy N++*](https://store.steampowered.com/app/230270/N_NPLUSPLUS/) *and* [*wishlist N+InfinityTimesTwo*](https://store.steampowered.com/app/3040020/N_PLUS_INFINITY_TIMES_TWO/) *on Steam!*

---

## FAQ

### Q. Why did you port this?

**A.** N+ has always held a special place in my heart. Enjoyed it on many amazing nights during LAN parties back in my senior year of high school. Unfortunately time hasn't been kind to N+ and it is currently unobtainable, the only way to play it being via emulation. Xenia introduces a very annoying "jittery Ninja" physics bug that irked me, so I made it a personal challenge to restore the game to its former glory and bring back some of the functionality lost to time.

### Q. How do I host online games?

**A.** Hosts need to forward UDP ports 1000 and 1001 on their router. Once in-game, go to Multiplayer -> System Link -> Create Lobby. Proceed through the menus - once you are at the player lobby screen, you can either invite people through Discord OR provide them your IP for a direct connect. 

### Q. How do I join online games?

**A.** Method A: Have the host send you an invite over discord, then accept the invite. 
Method B: Go to Multiplayer -> System Link -> Join game. You will get a pop-up asking for the hosts IP to connect to. Either enter an IP or use the drop-down to pick from a list of saved IP's. (You can name and save connections to make future joining faster.)
Be sure to ALLOW the game through your firewall if you get the prompt!

### Q. How do I obtain achievements?

**A.** Achievements are awarded with the same conditions as on console, and you will get a pop-up message once the conditions are met. Unobtainable Xbox Live Ranked achievements have been expanded to include local/online multiplayer, so they can now be earned again. You can track your profiles achievement progress in the launcher.

### Q. I see 'mute' icons in the multiplayer lobby... Is voice chat supported?

**A.** No. Original voice implementation was not good, and in a world where Discord is free I figured this feature was not worth my time.

### Q. Will there be any further updates to this port?

**A.** Possibly, just depends if there are any major bug-fixes needed. I have thoroughly tested this, but opening this up to the general public may expose new bugs.

### Q. Was AI used in making this port?

**A.** Yes, but I am no barbarian! I put a lot of time and work into it ensuring that this project is functional and authentic down to every detail. You won't be disappointed!

### Q. Can you add X feature to the game?

**A.** I've been getting requests to overhaul the level builder, add options for different physics, add social features, etc... While I think it'd be a lot of fun and would love to expand the project, I believe this needs to stay a preservation project. By no means do I want to inadvertently turn the developers own work into a competitor to their upcoming game. My recommendation is to enjoy this port as a stable and modernized way to experience the game with its original features and multiplayer. For people who are looking for new features, I recommend buying N++ and wishlisting N+InfinityX2, as well as following the progress of it to help the developers build the best sequel possible 🙂 

### Q. Is the source code available?

**A.** Negative! As previously mentioned, I do not want to add any features that would steal thunder from the devs upcoming game. I would feel very disappointed in myself if I enabled someone else to fork this port to pursue those changes. 

### Q. Does this project have a discord?

**A.** No, but you can find me around Discord if you'd like! -The Incredible Holc

### Q. I love this project, where can I donate?

**A.** Donations are not accepted. If you enjoy this game and love the N series, support the original devs! Go buy N++ and wishlist their newest upcoming N release, **[N Plus Infinity Times Two](https://store.steampowered.com/app/3040020/N_PLUS_INFINITY_TIMES_TWO/)**
