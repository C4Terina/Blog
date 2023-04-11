+++
author = "C4Terina"
title = "My RE roadmap"
date = "2023-04-11"
description = "My super beginner guide on how to self taught yourself RE"
tags = [
    "reverse-engineering",
]
+++
My beginner fliendly "guide" on how to learn reverse engineering. 
<!--more-->
After 22 long years of self discovery and therapy I've come to the realization that I really like being good at things that make me suffer mentally. This is why in 2022 I've started showing interest in the reverse engineering industry. Ever since I've collected a lot of material that has helped me in my learning journey and that I will share with you. 

**!!I'd like to clarify that I'm SELF TAUGHT and STILL A BEGINNER so I will be updating these lists quite often!!**

But first of all...why would you learn reverse engineering? 
In short: 
* you want to suffer 
* you like watching assembly code for 100 hours straight 
* you want to make cheat engines or crack software 
* you want to become a malware analyst/vulnerability researcher

In my case, I've been playing a lot of CTFS since 2019 and the reverse category has been my favourite. So with that said...here are my lists/tips: 

For CTFS: 
* Learn C.
* **Static analysis:** learn to use any decompiler/dissasembler of your choice (IDA/Ghidra/Binja/Cutter). Personally I use Ghidra but I've tried them all. 
* **Dynamic analysis:** learn to use any debugger of your choice. I use gdb with the peda extension. I haven't used gdb as much in CTFS, I usually analyze the binary statically. 
* Start learning some x86/x86-64. 
* Unfortunately start learning some python, will need it for challenges that have custom encryption.
* Play [PicoCTF](https://picoctf.org/) picogym challenges. Easy, fun and extremely beginner friendly. 
* Play reverse category from HackTheBox
* ...

Tips for CTFS:
* USEFUL COMMANDS file, strings, ltrace, strace...
* WATCH A LOT OF VIDEOS AND READ WRITEUPS!!! I can't stretch this enough. If you are completely new at this you NEED to have some sort of reference.
* NOT EVERY CHALLENGE IS A GOOD REVERSE CHALLENGE. Some have been an absolute pain in the ass to solve/understand. Others are unsolvable. 
* BE PATIENT. Some challenges have took me 15 hours to solve. 
* THE MORE YOU PLAY, THE MORE YOU LEARN. 
* ...

From a "professional" view:
* [Binary exploitation](https://www.youtube.com/watch?v=iyAyN3GFM7A&list=PLhixgUqwRTjxglIswKp9mpkfPNfHkzyeN) playlist by LiveOverFlow really helped me understand how this all works. 
* Watching malware analysis videos by [John Hammond](https://www.youtube.com/@_JohnHammond). 
* TryHackMe rooms: [Introduction to AntiVirus](https://tryhackme.com/room/introtoav), [Basic Static analysis](https://tryhackme.com/room/staticanalysis1), [AV Evasion: Shellcode](https://tryhackme.com/room/avevasionshellcode), [Intro to malware analysis](https://tryhackme.com/room/intromalwareanalysis), [Yara](https://tryhackme.com/room/yara), [Basic Malware RE](https://tryhackme.com/room/basicmalwarere), [MAL: REMnux - The Redux](https://tryhackme.com/room/malremnuxv2).[Dissecting PE Headers](https://tryhackme.com/room/dissectingpeheaders) and probably more...
* [Modern binary exploitation lecture by RPISEC](https://web.archive.org/web/20210710080726/http://security.cs.rpi.edu/courses/binexp-spring2015/)
* [Github with a lot of RE resources](https://github.com/wtsxDev/reverse-engineering)
* ...

General tips:
* Be consisent. It's hard I know. 
* Set small goals every week. Are you going to watch the first 5 videos of a playlist? Are you going to complete a tryhackme room? Are you going to solve a challenge? You decide.  
* You aren't dumb. Everything takes years of practice. Be patient. 
* Make it fun for yourself. I like rewarding myself after solving a difficult challenge or learning a complex topic. 