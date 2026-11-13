# N+ PC Port

Greetings Ninjas!

This PC port is a preservation project that lets people play the 2008 XBLA version of N+, which is unavailable on the Xbox Marketplace and is becoming lost media. This recomp is based on the ROM provided in the N++ Discord.

Because this is strictly a preservation project, new gameplay features outside the scope of the original game will not be added. Anyone wanting a new experience should **buy N++** and **wishlist N+InfinityTimesTwo** to support the devs!

Lastly, please direct all PC port questions and issues to **theincredibleholc** on Discord.

> [!IMPORTANT]
> **Do not bug the N+ developers or the official N++ Discord for support!**

## Features

- All original tutorials, levels, and DLC, with co-op game modes too.
- N+ game launcher to easily view and configure settings and toggle QoL enhancements.
- "System Link" repurposed for online peer-to-peer multiplayer. (The host **must** open UDP ports 1000 and 1001.)
- New video options for up to 4K rendering and frame rates beyond 60 FPS. (Via interpolation; physics still run at 60 Hz.)
- SDL3 input for keyboard and mouse or other brands of controller. (PlayStation, Nintendo, even Rock Band drums if you really wanted.)
- Discord Rich Presence integration: send multiplayer invites and join matches directly through Discord.
- Local profiles that save and track your episode progress, with completion stats in the launcher.
- Original Xbox 360 achievements, unlockable with in-game notifications.
- In-game level builder that supports playing your custom levels online. Players can also export their levels via the launcher and send them to others.

## Requirements

- Windows 10 or higher
- SSE4.2-compatible processor (AVX2 preferred)

*If you love this game, support the devs!* [**Buy N++**](https://store.steampowered.com/app/230270/N_NPLUSPLUS/) *and* [**wishlist N+InfinityTimesTwo**](https://store.steampowered.com/app/3040020/N_PLUS_INFINITY_TIMES_TWO/) *on Steam!*

---

## FAQ

### Why did you port this?

N+ has always held a special place in my heart. I enjoyed it on many amazing nights during LAN parties back in my senior year of high school. Unfortunately, time hasn't been kind to N+: it is currently unobtainable, and the only way to play it is through emulation. Xenia introduces a very annoying "jittery ninja" physics bug that irked me, so I made it a personal challenge to restore the game to its former glory and bring back some of the functionality lost to time.

### How do I host online games?

Hosts need to forward UDP ports 1000 and 1001 on their router. Once in-game, go to **Multiplayer → System Link → Create Lobby**. Proceed through the menus. Once you're at the player lobby screen, you can either invite people through Discord or give them your IP for a direct connection.

### How do I join online games?

- **Method A:** Have the host send you an invite over Discord, then accept the invite.
- **Method B:** Go to **Multiplayer → System Link → Join Game**. A pop-up will ask for the host's IP. Either enter an IP or pick one from the drop-down list of saved IPs. (You can name and save connections to make joining faster in the future.)

Be sure to **allow** the game through your firewall if you get the prompt!

### How do I obtain achievements?

Achievements are awarded under the same conditions as on console, and you'll get a pop-up message once the conditions are met. The unobtainable Xbox Live Ranked achievements have been expanded to include local and online multiplayer, so they can be earned again. You can track your profile's achievement progress in the launcher.

### I see "mute" icons in the multiplayer lobby. Is voice chat supported?

No. The original voice implementation was not good, and in a world where Discord is free, I figured this feature was not worth my time.

### Will there be any further updates to this port?

Possibly; it depends on whether any major bug fixes are needed. I have tested this thoroughly, but opening it up to the general public may expose new bugs.

### Was AI used in making this port?

Yes, but I am no barbarian! I put a lot of time and work into making sure this project is functional and authentic down to every detail. You won't be disappointed!

### Can you add X feature to the game?

I've been getting requests to overhaul the level builder, add options for different physics, add social features, and so on. While I think it would be a lot of fun and I'd love to expand the project, I believe this needs to stay a preservation project. By no means do I want to inadvertently turn the developers' own work into a competitor to their upcoming game.

My recommendation is to enjoy this port as a stable, modernized way to experience the game with its original features and multiplayer. If you're looking for new features, I recommend buying N++ and wishlisting N+InfinityTimesTwo, and following its progress to help the developers build the best sequel possible 🙂

### Is the source code available?

Negative! As mentioned above, I don't want to add any features that would steal thunder from the devs' upcoming game, and I would be very disappointed in myself if I enabled someone else to fork this port to pursue those changes.

### Does this project have a Discord?

No, but you can find me around Discord if you'd like! — The Incredible Holc

### I love this project. Where can I donate?

Donations are not accepted. If you enjoy this game and love the N series, support the original devs! Go buy N++ and wishlist their newest upcoming N release, [**N Plus Infinity Times Two**](https://store.steampowered.com/app/3040020/N_PLUS_INFINITY_TIMES_TWO/).
