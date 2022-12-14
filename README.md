# BLS Christmas Capture the Flag Challenge

## Summary
This is a small little server-based game created for the Black Lantern family! It is a Dungeons and Dragons type text-based adventure that focuses around your adventure at the Black Lantern Christmas Party! Download, play, and enjoy!

And... for those who like to poke around at things... there is a bug in the code of this text-based adventure. There will be an award for those who can find the bug, exploit it, and extract the CTF Key!

![dnd_005](https://user-images.githubusercontent.com/18358246/206772046-e4b5afe7-4811-4a61-af19-4110a706c974.png)

## How to play the game!
1. Star this repo!
1. Download the [executable](https://github.com/stryker2k2/bls-ctf/blob/master/dnd.exe) in this repo
1. Download [netcat](https://nmap.org/ncat/)
1. Run the program called `dnd.exe`
1. Connect to the locally running server by using `ncat localhost 379`
1. Enjoy!

## How to Capture the Flag!
1. Poke around the game until you find the hint and/or areas of interest
1. Statically Reverse Engineer the executable to find the vulnerability
1. Dynamically debug the executable and draft your exploit
1. Execute your exploit
1. Profit!

## Where is the flag?
You are looking for a flag that looks like...\
`BLS-CTF{Ex4mple_Fl4g}`

The local file will give you instruction on what to do next after you successfully exploit it. And, yes, this next step contains the actual winning flag which involves accessing the exact same dnd.exe file (matching SHA256 hash) on a remote server that has the same vulnerability and the same address space layout.

When you are ready to move to the next step, contact me via Microsoft Teams or @stryker2k2 on Twitter.

## Notes from the Developer
- Make sure you go down all of the different story paths! I spent a lot of time making the story paths entertaining!
- You will only be allowed to access the remote server after you send a screenshot proving that you've successfully exploited the local file
- Attempting an exploit against the remote server will cause the hosted process to crash; contact me to reboot the process
- Contact me via Microsoft Teams or @stryker2k2 on Twitter is you encounter problems/questions/issues
- dnd.exe SHA256 Hash: 03DD8BC4E10C8CF899EE707C3652E90E3A0F76E55A70B394EDD40FCAD643B8AC

## Pictures!
![dnd_004](https://user-images.githubusercontent.com/18358246/206769351-b28ad824-f4d1-4748-9c0c-c99bf20def1e.png)
