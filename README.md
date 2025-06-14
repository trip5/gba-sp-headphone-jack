# gba-sp-headphone-jack
 A list of headphone jack mods for the Game Boy Advance SP.
 
 There's a few options to choose. None are perfectly ideal IMO - there isn't a lot of space to fit the headphone jack. Consider the pros and cons of each before committing - remember to consider ergonomics and where you hands will usually rest.

 ## Direct connection warning

 Also, please note that Gekkio cautions doing direct connections:

> PSA: if you've added a headphone jack to a Game Boy Advance SP and didn't add any capacitors as part of the mod, you may have created a Headphone Destroyer Mod ™
> I'll need to do some testing after work to verify this, but here's an example calculation:
> 
> let's say you've bought AKG N40 earbuds, which cost $399.95. Specs:
> 
> Impedance: 20 ohm
> MAX input power 10mW
> 
> let's assume the Advance SP audio amplifier puts the DC offset at half of the supply voltage. I'll check the real value after work, but this is a reasonable assumption for now. For a stock 3.8V battery that means 1.9V
> so V=1.9V, R=56+20 -> P=VxV/R=1.9*1.9/76=47.5 mW
> 
> 47.5mW > 10mW
> -> bye AKG
> 

As a solution, makho suggests this:

> Instead, add 100 uF (or more) 6.3V (or more) capacitor in series for both channels. Positive side goes to the test point, and negative side to the corresponding jack pin. Alternatively, use an isolated switch between the switch pin and system ground instead of using system ground (gnd) as audio ground (agnd) on the headphone jack to switch to the switch pin.

## Under power LEDs
Might affect ergonomics! I personally have [no issue](under-power-LED-ergonomics.jpg).

Preview | Links and info
------------ | -------------
![](thumbnails/hackaday-173427-gba-sp-headphone-jack-mod.jpg) | [hackaday writeup](https://hackaday.io/project/173427-gba-sp-headphone-jack-mod)
![](thumbnails/imgur-da826qH.jpg) | [imgur post](https://imgur.com/a/da826qH), [Github backup](backups/imgur-da826qH/)
![](thumbnails/discord-orangeglo.png) | [discord post](https://discordapp.com/channels/246604458744610816/332487777986019337/734842804538179667), [Github backup](backups/discord-orangeglo.png)
![](thumbnails/youtube-W3H48VH9VDw.png) | [Youtube video](https://www.youtube.com/watch?v=W3H48VH9VDw)
![](thumbnails/gameboy-subreddit-FollowTheTrailofDead.jpg) | uses capacitors! [reddit post](https://www.reddit.com/r/Gameboy/comments/1l676l4/gameboy_advance_headphone_mod_and_a_misadventure/), [Github backup](backups/gameboy-subreddit-FollowTheTrailofDead/)

## Inside top screen
Requires IPS screen mod to free up enough space.

Preview | Links and info
------------ | -------------
![](thumbnails/youtube-L5i0NNrpfFw.png) | [makho Youtube](https://www.youtube.com/watch?v=L5i0NNrpfFw)

## Bottom-left screw post
Removes a screw post, so case isn't as tightly closed. Might affect ergonomics!

Preview | Links and info
------------ | -------------
![](thumbnails/imgur-mqhpRvp.jpg) | [imgur post](https://imgur.com/a/mqhpRvp), [Github backup](backups/imgur-mqhpRvp/)
![](thumbnails/youtube-MOywVfRrYTg.png) | [The Retro Future Youtube](https://www.youtube.com/watch?v=MOywVfRrYTg)
![](thumbnails/imgur-xWTdjy3.jpg) | [imgur post](https://imgur.com/gallery/xWTdjy3), [Github backup](backups/imgur-xWTdjy3/)

## Between L and R buttons
Cuts into the battery compartment - requires a smaller battery.

Preview | Links and info
------------ | -------------
![](thumbnails/imgur-aFbhm.jpg) | [imgur album aFbhm](https://imgur.com/a/aFbhm), [Github backup](backups/imgur-aFbhm/)

## In the hinge
Might reduce hinge strength/lifespan. Might affect ergonomics!

Preview | Links and info
------------ | -------------
![](thumbnails/discord-sammy.sam.jpg) | [discord post](https://discordapp.com/channels/246604458744610816/332487777986019337/733445195001102468), [Instagram post](https://www.instagram.com/p/CCzr_ZOlZCR/), [Github backup](backups/discord-sammy.sam/)

## USB-C dongle headphone jack
I personally don't want to need a dongle, but it's awesome to know this is an option!

Preview | Links and info
------------ | -------------
![](thumbnails/youtube-5_2sGFCsaPw.png) | [666Gothicgirl Youtube](https://www.youtube.com/watch?v=5_2sGFCsaPw), [reddit post](https://www.reddit.com/r/Gameboy/comments/e62yc5/complete_my_cover_for_the_usb_c_port_that_i_build/f9qq91v/), [imgur album ruIvKuk](https://imgur.com/a/ruIvKuk), [Github backup](backups/imgur-ruIvKuk/)

## Bluetooth audio
Hey, that's not a headphone jack at all!

Preview | Links and info
------------ | -------------
![](thumbnails/gameboy-subreddit-eg937m.jpg) | [reddit post](https://www.reddit.com/r/Gameboy/comments/eg937m/gameboy_advance_sp_bluetooth_audio_mod/), [additional reddit post](https://www.reddit.com/r/Gameboy/comments/gc5k7x/gba_with_bluetooth_audio/), [Github backup](backups/gameboy-subreddit-eg937m/), [personal website writeup](https://mmax.tech/?p=3895&lang=en), [writeup archive](https://web.archive.org/web/20201025163111/https://mmax.tech/?p=3895&lang=en)


# Other Gameboy Mods

[Mods - Game Boy Subreddit Wiki](https://www.reddit.com/r/GameBoy/wiki/mods)

## My Other Gameboy Mods

* [USB-C Mod for Gameboy Advance SP (and original Nintendo DS)](https://github.com/rorosaurus/gba-sp-usb-c/)
* [USB-C Mod for Nintendo DS Lite](https://github.com/rorosaurus/nds-lite-usb-c/)
* [USB-C Mod for Nintendo 3DS XL](https://github.com/rorosaurus/3ds-xl-usb-c/)
* [List of headphone jack mods for the Gameboy Advance SP](https://github.com/rorosaurus/gba-sp-headphone-jack/)