---
title: 'the thrills of linux'
description: 'my summary of using the joyous operating system(s) known as linux'
pubDate: 2026-02-03
tags: ['linux', 'os']
slug: "the-thrills-of-linux"
---

# the thrills of linux

i started using linux about 4 years ago. i can't particularly remember what drove me to do so, but i do remember thinking kali linux was pretty cool. though i never daily drove kali (would have been a terrible decision), i settled on a distro that seemed to be recommended to new linux users. good ol' boring ubuntu.

## ubuntu

ubuntu was okay. it doesn't look particularly impressive, but it was just fine enough to get me started on my journey to discovering what the linux nerds were always talking about. i learnt a bit of linux-fu here for a few months, and dabbled with the terminal a bit, but i was still largely dependent on the gui.

## linux mint

i spent quite a while on linux mint. it looked much nicer than ubuntu, but was still familiar enough not to cause any cognitive distress. i finally figured out gaming was possible on linux, and spent a good chunk of my time playing football manager. this was when i started getting a little annoyed with linux.

i had a benq 1440p 144hz monitor and i could not for the life of me get it to work at the advertised refresh rate. on windows i was able to display 1440p at 120hz, but i was stuck on 60hz here. still, it was probably the most fundamental part of my linux journey. i definitely familiarised myself with the terminal more, and found out that i was enjoying tinkering with my computer for hours on end.

## pop-os

pop-os! had my gpu working right out of the box. i was quite stunned as to how well games ran on it, so i daily drove this for a year as well. this was also when i discovered tiling. it was a simple concept but so refreshing. no more clicking around trying to find where a random window had been embedded. it was all right there for me to see and switch to with keyboard shortcuts. i think pop-os! is my favourite debian-based distro by far.

it wasn't without its quirks though. one day after messing around with the new cosmic desktop environment (it was in alpha to be fair), i found myself on the end of a strange error screen that wouldn't allow me to access my desktop. after some troubleshooting, i gave it up as a bad job and decided that my time with pop-os! was over.

## fedora

i'm not gonna lie, i really didn't like fedora. i think i used it for a total of 2 days. it felt so alien to me that i wasn't sure it was meant to even be usable by regular people at all. i guess after years of typing some variation of `sudo apt` all the time, installing packages on fedora appeared absolutely outlandish to me. even installing codecs for video playback was a hassle that involved some shenanigans i no longer remember. i'm sure fedora is fine, and a lot of people who use fedora really like it. but sadly i gave it up as a bad job.

## arch

while searching for a new distro, i came across something so interesting that i had to try it out for myself. it was the [end-4 dotfiles](https://github.com/end-4/dots-hyprland) for arch linux. suddenly i was thrust into a whole new landspace of linux. *arch linux? isn't that supposed to be hard? it's not supposed to be used for actual work and stuff, right? cause you can brick your system just from an update!* but looking at the fluidity and animations of end-4's quickshell config made me very, very excited to try it out.

### end-4 dotfiles

so i whipped out my ventoy flash drive yet again and installed it. end-4 made it surprisingly easy to install. all i had to do was install endeavouros (arch-based distro) with no desktop environment, and run the install command provided on their github.

after an hour or two, i was in. and it was glorious. a bit on the anime weeb side, but it just felt so different. [hyprland](https://hypr.land/) as the tiling wm was so fresh and snappy. ai chatbots built into the desktop ui, keyboard shortcut based navigation, so much customisability, the whole shebang. i was sure this would be my final endgame. then i noticed something: my gpu was doing a little bit more work than i was normally used to. then i noticed the lag that would sometimes occur when i did anything remotely demanding. i tried to stand it, but after some time i just came to the realisation that my integrated graphics weren't going to be enough for a completely smooth experience.

### omarchy

enter [omarchy](https://omarchy.org/). now i was very much aboard the hyprland train. after having tried and failed to configure my own custom arch setup with hyprland and waybar to my liking, i came across a recommendation on the hyprland wiki to try a config named 'omarchy'. i took a look at it and thought, "hey. this looks simple and clean. very minimal, so hopefully my system can actually handle this." so i reinstalled arch again, and ran the omarchy setup.

i think omarchy is very very good. it does all the basics well, and provides arch linux newbies a really good foundation to start with. but i did notice something that was getting on my nerves. some things weren't working they way they were supposed to, and i couldn't figure out *why*. my main issue was with my logitech mouse. i had remapped the side buttons to change workspace back and forth depending on which button was pressed. this had worked fine on my own arch + hyprland config, but in omarchy, it was broken. it would sometimes do what it was supposed to, but more often it just activated the control modifier key indefinitely. i even reinstalled regular arch + hyprland just to make sure i wasn't crazy, but nope, it was omarchy. after trying to get help, i realised that it was just a niche problem that i couldn't figure out how to solve, because i didn't really understand what omarchy was doing under the hood. i could have spent hours and hours of my time combing through the base config files and finding out what was changing what, but that didn't sound very fun to me. admittedly, i may have found the motivation if only i didn't also notice that omarchy's updates were breaking my custom configuration. things like waybar would get updates from omarchy and suddenly the configs i had made were suddenly replaced by the stock config (with your own config being backed up in the same folder). so the os wasn't really mine. it would always be at the mercy of whatever dhh wanted to do with it.

and speaking of dhh..., let's just say i did not find the man's politics very appealling once i started looking into them a little bit more. i just knew him as the ruby on rails guy, and since i don't check social media or hang out in dev spaces, i never heard of his controversies. but i guess they had gotten a bit much, and were the talk of many a discord channel.

with all that, i decided to drop omarchy. i still think it's a really good distro for anyone getting started in linux (of course, that's subjective. you'd have to put in the time and effort to understand what's happening under the hood and how to fix things).

so what now?

### niri + dms

currently i am using niri with dankmaterialshell. i moved from hyprland to niri randomly one day after coming across [a tweet from soulpee](https://x.com/soulpee/status/1994159306954969098). i had heard of niri, but never properly looked into it, so my curiosity was piqued.

[niri](https://github.com/YaLTeR/niri/) is a scrolling wayland compositor. essentially it means that your windows will appear next to each other horizontally, and will extend infinitely beyond the limits of your display. immediately i saw the appeal to this. no longer did i have to deal with hyprland's dwindle layout making my windows too small, forcing me to send some of them to another workspace. it was also lighter than hyprland in terms of resources, had good enough documentation, less controversy, and a pretty nice community.

[dankmaterialshell](https://danklinux.com/) (dms) was made with niri in mind, and it was much less resource-intensive than end-4's setup. i like it a lot, especially the material ui design choice. it's customisable enough for my needs and never gets in the way. it also provides a few nice-to-haves such as a native clipboard manager, notepad, pomodoro timer, and weather and calendar integrations.

arch definitely taught me the most about linux (yes i did forget to install a bootloader once when setting it up, and wondered what was happening when i couldn't boot into any OS), and i highly recommend everyone tries it, after getting their feet wet with an "easier" distro. pacman and aur helpers are so good i would continue using arch just for their utility alone. arch opens you up to the possibility of actually making your system your own, as you are no longer bound to use any specific desktop environment or window manager. after installing arch, all you have is a blinking terminal cursor and the world as your oyster.
