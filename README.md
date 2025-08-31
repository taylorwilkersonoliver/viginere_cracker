Elite: Dangerous is a pretty fun game and there was a community event that required decrypting a message. 
As far as I could see, there wasn't a PoC for decryption, so here is a way to come up with the answer.

Here is the message from the game:


"""
30 AUG 3311
COMMUNICATION BEACON
THERE'S A SECRET THEY DON'T WANT US TO KNOW

DECODING MESSAGE….TORA CODEX PROTOCOL///
I'm aboard. My contact came through and my sources were right, something is definitely being kept a secret but nobody knows why. I managed to scan their jump manifest but it's incomplete, sorry.

Best thing you can do is find this ship and scan the manifest properly for all locations. I can't transmit again for fear of being discovered. The location order is listed, so my guess is that you will only be able to locate the ship in the target systems in short intervals.

According to the manifest, it should restart a new run on 31st August at 18:00 UGT.

I'm encrypting the manifest.
If in ##doubt## your student, Vigenere, has the key.
ycxztnogbgd hbsxh
qiebfeo iox
polgbf tivk
jfugylom upr
xduobnzct yljy
"""

The result:

Found key length: 5, key: 'doubt' (shifts [3, 14, 20, 1, 19])

Decryption: (key continues across lines: False)
  vodyakamana three
  nukamba one
  marfic four
  graffias two
  upaniklis five


The first word of each line is a system in the game followed by the order in which the megaship will be visiting each system.

Nukamba: https://inara.cz/elite/starsystem/10258/  
Graffias: https://inara.cz/elite/starsystem/393702/  
Vodyakamana: https://inara.cz/elite/starsystem/10220/  
Marfic: https://inara.cz/elite/starsystem/27700/  
Upaniklis: https://inara.cz/elite/starsystem/10408/  


Reference link:
https://inara.cz/elite/cmdr-logbook-entry/35228/88804/  
